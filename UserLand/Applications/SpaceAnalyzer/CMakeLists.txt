compile_gml(SpaceAnalyzer.gml SpaceAnalyzerGML.h space_analyzer_gml)

set(SOURCES
    main.cpp
    TreeMapWidget.cpp
    SpaceAnalyzerGML.h
)

pranaos_app(SpaceAnalyzer ICON app-space-analyzer)
target_link_libraries(SpaceAnalyzer LibDesktop LibGfx LibGUI)
