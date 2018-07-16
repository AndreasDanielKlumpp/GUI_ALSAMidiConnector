# ALSAguiTOOLS
GUI tools for midi connecting and recording tasks
ALSAguiTOOLS are Qt GUI (gnome-terminal required) tools for midi connecting and recording tasks on Linux systems with Alsa (aconnect), but without the need of a DAW or Jack Audio Connection Kit (made for small screens e.g. to turn via qmidiarp a raspberry pi into an arpeggiator..).

for Debian 9 add to .pro file:
CONFIG += c++11

required:
libasound2-dev

start qmidiarp in alsa mode:
qmidiarp -a


AlsaMidiRec is a GUI for arecordmidi.c (with midi input selection menu) for 'point-and-shoot' midi recording tasks on Linux systems with Alsa, but without the need of a DAW or Jack Audio Connection Kit. 

AlsaMidiRec requires alsa-utils (including arecordmidi) installed on the system (for debug: libasound2 and libasound2-dev). The midi files of the selected midi input will be saved with date and time in the folder of AlsaMidiRec. 

AlsaMidiRec: Copyright (c) 2016 A. Klumpp

arecordmidi.c:  Copyright (c) 2004-2005 Clemens Ladisch <clemens@ladisch.de>

 *  This program is free software; you can redistribute it and/or modify
 *  it under the terms of the GNU General Public License as published by
 *  the Free Software Foundation; either version 2 of the License, or
 *  (at your option) any later version.
 *
 *  This program is distributed in the hope that it will be useful,
 *  but WITHOUT ANY WARRANTY; without even the implied warranty of
 *  MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
 *  GNU General Public License for more details.
 *
 *  You should have received a copy of the GNU General Public License
 *  along with this program; if not, write to the Free Software
 *  Foundation, Inc., 59 Temple Place, Suite 330, Boston, MA  02111-1307 USA
 *


//AlsaConnectorGUI is a Qt GUI (gnome-terminal required) for midi connecting tasks on Linux systems with Alsa (aconnect), but without the need of a DAW or Jack Audio Connection Kit.

//AlsaConnectorGUI: Copyright (c) 2016 A. Klumpp


// *  This program is free software; you can redistribute it and/or modify
// *  it under the terms of the GNU General Public License as published by
// *  the Free Software Foundation; either version 2 of the License, or
// *  (at your option) any later version.
// *
// *  This program is distributed in the hope that it will be useful,
// *  but WITHOUT ANY WARRANTY; without even the implied warranty of
// *  MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
// *  GNU General Public License for more details.
// *
// *  You should have received a copy of the GNU General Public License
// *  along with this program; if not, write to the Free Software
// *  Foundation, Inc., 59 Temple Place, Suite 330, Boston, MA  02111-1307 USA
// *

