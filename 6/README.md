Sparky 6 Core
This meta package will install SparkyLinux 6 base components.

Copyright (C) 2019-2021 Paweł Pijanowski

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
base-files (>= 11~sparky0)
libc6 (>= 2.28)
sparky-apt (>= 20210715~sparky6~0)
sparky-artwork
sparky-info
sparky-keyring
sparky-remsu
sparky6-theme
tela-icon-theme

Recommends:
-------------
sparky-grub-theme (no armhf)
sparky-plymouth

Conflicts:
-------------
sparky-core-x86
sparky-core-arm
sparky-core (<= 6.20190725)

Replaces:
--------------
sparky-core-x86
sparky-core-arm
sparky-core (<= 6.20190725)

Install:
-------------
This is a meta package, so install dependencies only.
