project(ImGui)

add_library(imgui STATIC)

target_include_directories(imgui PUBLIC ./)

target_sources(imgui PRIVATE
    imconfig.h
    imgui.h
    imgui.cpp
    imgui_draw.cpp
	  imgui_internal.h
  	imgui_widgets.cpp
    imgui_tables.cpp
  	imstb_rectpack.h
  	imstb_textedit.h
  	imstb_truetype.h
  	imgui_demo.cpp
)
