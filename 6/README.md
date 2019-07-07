Sparky 6 Core
This meta package will install SparkyLinux 6 base components.

Copyright (C) 2019 Paweł Pijanowski

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>.

Dependencies:
-------------
base-files (>= 10~sparky0)
libc6 (>= 2.28)
sparky-apt (>= 20190127)
sparky6-apt
sparky-artwork
ultra-flat-icons
sparky-info
sparky-keyring
sparky-remsu
sparky5-theme | sparky6-theme

Recommends:
-------------
sparky-grub-theme
sparky-plymouth

Conflicts:
-------------
sparky-core-x86
sparky-core-arm

Replaces:
--------------
sparky-core-x86
sparky-core-arm

Install:
-------------
This is a meta package, so install dependencies only.
