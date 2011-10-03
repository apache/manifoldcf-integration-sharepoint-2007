# Licensed to the Apache Software Foundation (ASF) under one or more
# contributor license agreements. See the NOTICE file distributed with
# this work for additional information regarding copyright ownership.
# The ASF licenses this file to You under the Apache License, Version 2.0
# (the "License"); you may not use this file except in compliance with
# the License. You may obtain a copy of the License at
#
# http://www.apache.org/licenses/LICENSE-2.0
#
# Unless required by applicable law or agreed to in writing, software
# distributed under the License is distributed on an "AS IS" BASIS,
# WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
# See the License for the specific language governing permissions and
# limitations under the License.

Instructions for locating wsdls needed for building the Apache SharePoint ManifoldCF Plugin:

(1) Install Microsoft Visual Studio.
(2) Install SharePoint 3.0 (2007).
(3) In the directory c:\Program Files\Microsoft SDKs\Windows\V6.x\bin, locate the utility "disco.exe".
(4) You will need the following Microsoft SharePoint wsdl:

Permissions.wsdl

Obtain this as follows:

disco /out:<output_directory> "http://<server_name>/_vti_bin/Permissions.asmx"

The resulting Permissions.wsdl file should be placed in the same directory as this README.txt.






