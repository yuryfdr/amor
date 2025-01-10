add_subdirectory( pics )
add_subdirectory( icons )

install( FILES
    tips-en
    blobrc
    ghostrc
    eyesrc
    bonhommerc
    nekorc
    nekokurorc
    pingurc
    wormrc
    billyrc
    bsdrc
    tuxrc
    taorc
  DESTINATION ${KDE_INSTALL_DATADIR}/amor
)

# TODO $(LN_S) $(amordir)/tips-en $(DESTDIR)$(amordir)/tips
