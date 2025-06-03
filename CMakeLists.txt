
cmake_minimum_required(VERSION 3.5)
project(robotnik_sensors)

find_package(ament_cmake REQUIRED)

install(DIRECTORY meshes urdf
  DESTINATION share/${PROJECT_NAME}/
)

ament_package()