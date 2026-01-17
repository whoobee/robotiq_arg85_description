cmake_minimum_required(VERSION 3.8)
project(robotiq_arg85_description)

find_package(ament_cmake REQUIRED)

install(
  DIRECTORY launch meshes robots
  DESTINATION share/${PROJECT_NAME}
)

ament_package()