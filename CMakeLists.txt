cmake_minimum_required(VERSION 3.12.4...3.14.5)
project(cmakehello VERSION 0.1.0
	DESCRIPTION "Tool that demonstrates modern cmake practices in c prohect"
        HOMEPAGE_URL "https://github.com/souryogurt/cmakehello"
	LANGUAGES C)

add_executable(cmakehello cmakehello/entry.c)
target_compile_features(cmakehello PUBLIC c_std_11)
