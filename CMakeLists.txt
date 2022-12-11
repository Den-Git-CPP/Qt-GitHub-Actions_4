cmake_minimum_required(VERSION 3.15)

project (GitHub-Actions_4 VERSION 0.0.1)

add_executable(GitHubActionsCPP 
main.cpp
)

enable_testing()

install(TARGETS GitHubActionsCPP RUNTIME DESTINATION bin)



