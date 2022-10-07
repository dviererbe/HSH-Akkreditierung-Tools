[![License badge for GNU Affero General Public License v3.0 or later](https://img.shields.io/badge/License-AGPL--3.0--or--later-informational)](https://www.gnu.org/licenses/gpl-3.0-standalone.html)

*⚠️ The source code is currently not included in this Repository because I am in the process of checking the legality of publishing it.*

# Accreditation Document Management Tools (for Harz University - Faculty of Automation and Computer Science)

A collection of tools, written in C#, which I developed for my job at the [Faculty of Automation and Computer Science](https://www.hs-harz.de/en/study/faculty-of-automation-and-computer-science) of the [Harz University](https://www.hs-harz.de/en/) to help checking records for inconsistencies, entering new data, and creating the curriculum handbooks. The records were spread over hundreds of Excel files and any change was entered manually. The handbooks were generated from LuaTeX files. I created a docker image to standardize the build environment. This simplified the complex installation process of LuaTeX for new staff members and eliminated different outputs, because of missing fonts on the computers of the employees. I also developed a collection of parsers that cross-checked the values of the records for inconsistencies. The initial run found over 150 errors (mostly typos) in a few minutes rather than days. Before I left, I worked on a Blazor Server Side Web Application that could display the Excel records in a simple Web UI and eliminated the waiting time to open the Excel files. Additionally, this UI prevented entering invalid data in the first place.

## License

Accreditation Document Management Tools    
Copyright (C) 2019-2022 Dominik Viererbe

This program is free software: you can redistribute it and/or modify it under the terms of the GNU Affero General Public License as published by the Free Software Foundation, either version 3 of the License, or *(at your option)* any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU Affero General Public License for more details.

You should have received a copy of the GNU Affero General Public License along with this program. If not, see <<https://www.gnu.org/licenses/>>.