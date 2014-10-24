
# rtc.io build resources

This is a repo that provides you tools for building WebRTC application on mobile devices. It will include different scripts to help you generate mobile packages.

## signApp.sh

This is a tool that does sign/re-sign your .app or .ipa packages and repacks into .ipa for installation on iOS devices.

```bash
usage: ./signApp.sh source identity [-p provisioning] [-e entitlements] target.ipa

source: input a .app or .ipa file for signning

identity: common name of your apple certificate to be used with -p provisioning

provisioning: Sign .ipa file with .mobileprovision

target.ipa: output a .ipa file

./signApp.sh /path/to/source.app "iPhone Developer: build rtc(XXXXXXXX)" -p xxx.mobileprovision output.ipa
```
## License(s)

### Apache 2.0

Copyright 2014 National ICT Australia Limited (NICTA)

   Licensed under the Apache License, Version 2.0 (the "License");
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at

     http://www.apache.org/licenses/LICENSE-2.0

   Unless required by applicable law or agreed to in writing, software
   distributed under the License is distributed on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
   See the License for the specific language governing permissions and
   limitations under the License.
