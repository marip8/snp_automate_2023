cmake_minimum_required(VERSION 3.5.0)

project(snp_automate_2023 VERSION 0.1.0 LANGUAGES C CXX)

find_package(ament_cmake REQUIRED)

install(
  DIRECTORY launch
            config
            urdf
            meshes
  DESTINATION share/${PROJECT_NAME}/)

ament_package()
