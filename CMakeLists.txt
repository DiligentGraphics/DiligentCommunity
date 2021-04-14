cmake_minimum_required (VERSION 3.6)

project(DiligentCommunity)

# Create a custom target to run source code formatting validation command
add_format_validation_target(DiligentCommunity "${CMAKE_CURRENT_SOURCE_DIR}" DiligentCommunity)

