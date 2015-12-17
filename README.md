# PROXMARK3 - HID CORPORATE 1000 BRUTEFORCER (STAND-ALONE MODE)

This version of Proxmark3 firmware adds one extra stand-alone mode to proxmark3 firmware.
The new stand-alone mode allows to execute a bruteforce on HID Corporate 1000 readers, by reading a specific badge
and bruteforcing the Card Number (incrementing and decrementing it), mainteining the same Facility Code of the 
original badge.

Based on an idea of Brad Antoniewicz of McAfee® Foundstone® Professional Services (ProxBrute), tha stand-alone mode has been
rewritten in order to overcome some limitations of ProxBrute firmware, that does not consider parity bits.

Created by:
- Federico Dotta - Security Expert at @ Mediaservice.net
- Maurizio Agazzini - Senior Security Advisor at @ Mediaservice.net

Installation:
- Download sources and compile it OR
- Download the release from the "Releases" section

Stand-alone mode diagram:
![alt tag](https://raw.githubusercontent.com/federicodotta/proxmark3/master/StandAloneModeDiagram.png)

**Use at your own risk. The authors are not responsable to any damagings, malfunctioning or issues caused by the code or by the use of the code.**

# INTRODUCTION:

The proxmark3 is a powerful general purpose RFID tool, the size of a deck
of cards, designed to snoop, listen and emulate everything from
Low Frequency (125kHz) to High Frequency (13.56MHz) tags.

This repository contains enough software, logic (for the FPGA), and design
documentation for the hardware that you could, at least in theory,
do something useful with a proxmark3.

# RESOURCES:

   * This repository!
      https://github.com/Proxmark/proxmark3
      
   * The Wiki
      https://github.com/Proxmark/proxmark3/wiki
      
   * The GitHub page
      http://proxmark.github.io/proxmark3/
      
   * The Forum
      http://www.proxmark.org/forum
      
   * The IRC chanel
       irc.freenode.org #proxmark3
       -or-
       http://webchat.freenode.net/?channels=#proxmark3
   
# DEVELOPMENT:

The tools required to build  or run the project will vary depending on
your operating system. Please refer to the Wiki for details.

   * https://github.com/Proxmark/proxmark3/wiki

# OBTAINING HARDWARE:

The Proxmark 3 is available for purchase (assembled and tested) from the
following locations:

   * http://proxmark3.com/
   * http://www.xfpga.com/

Most of the ultra-low-volume contract assemblers could put
something like this together with a reasonable yield. A run of around
a dozen units is probably cost-effective. The BOM includes (possibly-
outdated) component pricing, and everything is available from Digikey
and the usual distributors.

If you've never assembled a modern circuit board by hand, then this is
not a good place to start. Some of the components (e.g. the crystals)
must not be assembled with a soldering iron, and require hot air.

The schematics are included; the component values given are not
necessarily correct for all situations, but it should be possible to do
nearly anything you would want with appropriate population options.

The printed circuit board artwork is also available, as Gerbers and an
Excellon drill file.


# LICENSING:

This program is free software; you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation; either version 2 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program; if not, write to the Free Software
Foundation, Inc., 51 Franklin St, Fifth Floor, Boston, MA  02110-1301  USA


Jonathan Westhues
user jwesthues, at host cq.cx

May 2007, Cambridge MA
