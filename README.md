# SYN_automakefile_2019

Write a shell script named automakefile, that generates a nice Makefile given a configuration file.
This configuration file can contain the following (potentially unordered) lines:
* source_filename;dependence1 dependence2. . .
(specify the full names of the files, from the header subfolder below)
* PROJECT_DIR;name_of_the_project_root_folder
* SOURCES_DIR;subfolder_containing_the_source_files
* HEADERS_DIR;subfolder_containing_the_header_files
* LIBS_DIR;subfolder_containing_librairies
* EXEC;executable_name
* CC;compilator_binary
* CFLAGS;compilation_flag1 compilation_flag1. . .
* LDFLAGS;linking_flag1 linking_flag2. .
