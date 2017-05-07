FILE(GLOB assets assets/*.png)
install( FILES ${assets} DESTINATION ${DATA_INSTALL_DIR}/themes/Ghost/assets/ )

FILE(GLOB gtk-2.0 gtk-2.0/gtkrc)
install( FILES ${gtk-2.0} DESTINATION ${DATA_INSTALL_DIR}/themes/Ghost/gtk-2.0/ )

FILE(GLOB gtk-3.0 gtk-3.0/gtk.css)
install( FILES ${gtk-3.0} DESTINATION ${DATA_INSTALL_DIR}/themes/Ghost/gtk-3.0/ )
