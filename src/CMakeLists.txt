if(NOT CERES_FOUND)
add_subdirectory(ceres-solver)
endif()
add_subdirectory(camera_models)
add_subdirectory(camera_systems)
add_subdirectory(dbow2)
add_subdirectory(examples)
add_subdirectory(features2d)
add_subdirectory(gpl)
add_subdirectory(infrastr_calib)
add_subdirectory(location_recognition)
add_subdirectory(pose_estimation)
add_subdirectory(pugixml)
add_subdirectory(radialpose)
add_subdirectory(SiftGPU)
add_subdirectory(sparse_graph)
