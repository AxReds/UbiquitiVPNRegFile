# UbiquitiVPNRegFile
Enable Windows 10/11 L2TP VPN Client to Connect to Ubiquiti VPN Server

Reg File: to allow L2TP VPN Client to Connect to Ubiquiti VPN Server
Copyright (C) 2020 Alessio Rossini <alessior@live.com>

Original source code available at https://github.com/AxReds
Purpose: Enable Windows 10 and 11 to connect to a Ubiquiti VPN Server using MS-CHAP Protocol

Licensing: This program is free software; you can redistribute it and/or modify it under the terms of the GNU General Public License Version 3 as published by the Free Software Foundation.
This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.
See the GNU General Public License for more details https://opensource.org/
You should have received a copy of the GNU General Public License along with this program; 
if not, write to the Free Software Foundation, Inc., 59 Temple Place, Suite 330, Boston, MA 02111-1307 USA

How to use it, after having created a VPN Server on your Ubiquiti network (many tutorials are available on YouTube):

1) Execute the regfile by simply double clicking it or importing in RegEdit on Windows
2) Enable MS-CHAP Protocol under:
		Control Panel>Network & Internet>Network & Sharing Center>Change Adapter Setting>YOUR_VPN_CONNECTION>Properties>Security>Allow these protocols
3) Reboot your PC
4) Connect to your VPN
