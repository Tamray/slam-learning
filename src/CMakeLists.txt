add_library(trslam SHARED
        viewer.cpp
        config.cpp
        dataset.cpp
        frontend.cpp
        map.cpp
        mappoint.cpp
        camera.cpp
        )

target_link_libraries(trslam
        ${THIRD_PARTY_LIBS})
