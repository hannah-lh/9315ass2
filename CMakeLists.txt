cmake_minimum_required(VERSION 3.14)
project(C_ENV_SETTING C)

set(CMAKE_C_STANDARD 11)

# x1的测试文件
# 缺少.h文件或者.c文件的可以自己加

add_executable(x1_test
        x1.c
        bits.h
        bits.c
        reln.h
        reln.c
        defs.h
        tuple.h
        tuple.c
        page.h
        page.c
        )

# x2的测试文件
# 缺少.h文件或者.c文件的可以自己加
add_executable(x2_test
        x2.c
        bits.h
        bits.c
        reln.h
        reln.c
        defs.h
        tuple.h
        tuple.c
        page.h
        page.c
        tsig.c
        tsig.h
        )

# x3的测试文件
# 缺少.h文件或者.c文件的可以自己加
add_executable(x3_test
        x3.c
        bits.h
        bits.c
        reln.h
        reln.c
        defs.h
        tuple.h
        tuple.c
        page.h
        page.c
        tsig.c
        tsig.h
        )
