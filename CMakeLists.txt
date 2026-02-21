cmake_minimum_required(VERSION 3.22)

project(aminals)

# JUCE framework for platform layers 
add_subdirectory(JUCE)

# Shared code 
add_subdirectory(aminal_core)

# Target
add_subdirectory(flocks)
