# Generated from manual.pro.

add_subdirectory(buttons)
add_subdirectory(dialogs)
add_subdirectory(fonts)
add_subdirectory(gifs)
add_subdirectory(headerview)
add_subdirectory(qquickdialog)
add_subdirectory(screenshots)
add_subdirectory(styles)
add_subdirectory(styles-cover-flow)
add_subdirectory(testbench)
if(QT_FEATURE_systemtrayicon)
    add_subdirectory(systemtrayicon)
endif()
if(TARGET Qt::Widgets)
    add_subdirectory(viewinqwidget)
endif()
