# Changelog

## v0.0.4

  * New features
    * Added hardware signal support (rts, cts, dtr, dsr, etc.)
    * Added support for sending breaks
    * Added support for specifying which queue to flush
      (:receive, :transmit, or :both)

  * Bugs fixed
    * Fixed crash in active mode when sending and receiving
      at the same time

## v0.0.3

  * Bugs fixed
    * Crosscompiling on OSX works now

## v0.0.2

  * Bugs fixed
    * Fix hex.pm release by not publishing .o files

## v0.0.1

  * Initial release