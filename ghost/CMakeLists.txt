install(FILES colors metadata.desktop DESTINATION ${PLASMA_DATA_INSTALL_DIR}/desktoptheme/ghost/)

FILE(GLOB widgets widgets/*.svgz)
install( FILES ${widgets} DESTINATION ${PLASMA_DATA_INSTALL_DIR}/desktoptheme/ghost/widgets/ )

FILE(GLOB dialogs dialogs/*.svgz)
install( FILES ${dialogs} DESTINATION ${PLASMA_DATA_INSTALL_DIR}/desktoptheme/ghost/dialogs/ )

FILE(GLOB fifteenPuzzle fifteenPuzzle/*.svgz)
install( FILES ${icons} DESTINATION ${PLASMA_DATA_INSTALL_DIR}/desktoptheme/ghost/fifteenPuzzle/ )

FILE(GLOB lancelot lancelot/*.svgz)
install( FILES ${icons} DESTINATION ${PLASMA_DATA_INSTALL_DIR}/desktoptheme/ghost/lancelot/ )

FILE(GLOB opaque opaque/*.svgz)
install( FILES ${icons} DESTINATION ${PLASMA_DATA_INSTALL_DIR}/desktoptheme/ghost/opaque/ )

FILE(GLOB weatherstation weatherstation/*.svgz)
install( FILES ${icons} DESTINATION ${PLASMA_DATA_INSTALL_DIR}/desktoptheme/ghost/weatherstation/ )
