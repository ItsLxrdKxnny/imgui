add_library(
    ImGuiLib SHARED

    imgui.h
    imgui.cpp
    imgui_internal.h
    imgui_demo.cpp
    imgui_draw.cpp
    imgui_tables.cpp
    imgui_widgets.cpp

    backends/imgui_impl_dx11.h
    backends/imgui_impl_dx11.cpp
    backends/imgui_impl_win32.h
    backends/imgui_impl_win32.cpp
)

target_include_directories(ImGuiLib PUBLIC ${CMAKE_CURRENT_SOURCE_DIR})
