cmake_minimum_required(VERSION 3.28)
project(imguizmo)
set(SRC ImGuizmo.cpp ImGradient.cpp ImCurveEdit.cpp ImSequencer.cpp)

add_library(${PROJECT_NAME} STATIC ${SRC})
target_include_directories(${PROJECT_NAME} PUBLIC ${REAL_PUBLIC_INCLUDE_DIRS})
