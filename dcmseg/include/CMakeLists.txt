# declare installation files
INSTALL(DIRECTORY dcmtk/dcmseg DESTINATION "${CMAKE_INSTALL_INCLUDEDIR}/dcmtk" COMPONENT include FILES_MATCHING PATTERN "*.h" PATTERN "CVS" EXCLUDE)
