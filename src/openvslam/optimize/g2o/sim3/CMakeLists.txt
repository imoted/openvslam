target_sources(${PROJECT_NAME} PRIVATE
        ${CMAKE_CURRENT_SOURCE_DIR}/shot_vertex.cc
        ${CMAKE_CURRENT_SOURCE_DIR}/graph_opt_edge.cc
        ${CMAKE_CURRENT_SOURCE_DIR}/transform_vertex.cc
        ${CMAKE_CURRENT_SOURCE_DIR}/backward_reproj_edge.cc
        ${CMAKE_CURRENT_SOURCE_DIR}/forward_reproj_edge.cc)
