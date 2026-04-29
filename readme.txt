DayZ Complete Cars With Fuel & Either An M4A1, Hunting, Fishing Or Farming Items In Cargo XML Mod Changelog & Terms Of Use

This XMl mod will make new spawns of Cars spawn complete & with fuel & Either An M4A1, Hunting, Fishing Or Farming Items In Cargo.

This is part of scalespeeder gamings modular loot / CLE modding system, which is designed to be update independant, simple to install  and highly customizable.

Limited Testing on PC Chernarus Local Server DAYZ  Version 1.29 April 2026.

Designed to work with PC, PlayStation & Xbox DayZ Community Servers, for all maps that use these vehicles.

Created by @scalespeeder. Please report bugs & errors to scalespeeder@gmail.com with screenshots.

TERMS OF USE
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS
OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN
AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH
THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

Using these modded xml files could break the functioning of your DAYZ server, requiring a reinstall that would wipe
all player progress.

Using these modded xml files neccessitates increased regular restarts to prevent server crashing.

It is suggested you thoroughly test your server after applying these files to ensure proper
functioning of your server.

-----------------------

PLEASE READ THE INSTRUCTIONS ON HOW TO INSTALL THESE FILES

To download the files from Github click the green "code" button, then "download zip" then extract the files to your local PC.

-----------------------

Included are seperate files for the various colours of the CivilianSedan , Sedan_02, OffroadHatchback & Hatchback_02 to make fresh spawns spawn complete with fuel & Either An M4A1, Hunting, Fishing Or Farming Items In Cargo.
 
CivilianSedan (Olga) Fishing Items

Sedan_02 (Sarka) Farming Iems

OffroadHatchback (Ada) M4a1

Hatchback_02 (Gunter) Hunting Items


You can use which ones you prefer. These files DO NOT alter the number of cars that will spawn.

Stop your server.

On console you already have a "custom" folder inside the mission folder on your server. ON PC YOU MUST MAKE ONE, eg: mpmissions\dayzOffline.chernarusplus\custom

Now upload the files of your choice

Veh-CivilianSedan-complete-with-FRod-cfgspawnabletypes.xml

and / or

Veh-Sedan_02-complete-with-Farming-cfgspawnabletypes.xml

and / or

Veh-OffroadHatchback-complete-with-M4A1-cfgspawnabletypes.xml

and / or

Veh-Hatchback_02-complete-with-Hunting-cfgspawnabletypes.xml

into your custom folder.

Next open up your vanilla cfgeconomycore.xml, and near the bottom, above the closing

</economycore>

tag, to use all the files,

paste this:

	<ce folder="custom">
	<file name="Veh-CivilianSedan-complete-with-FRod-cfgspawnabletypes.xml" type="spawnabletypes" />
   	<file name="Veh-Sedan_02-complete-with-Farming-cfgspawnabletypes.xml" type="spawnabletypes" />
	<file name="Veh-OffroadHatchback-complete-with-M4A1-cfgspawnabletypes.xml" type="spawnabletypes" />
	<file name="Veh-Hatchback_02-complete-with-Hunting-cfgspawnabletypes.xml" type="spawnabletypes" />
	</ce>

If you only want to use one type of car, simply delete the lines for the files you don't want.

eg

	<ce folder="custom">
  	<file name="Veh-OffroadHatchback-complete-with-M4A1-cfgspawnabletypes.xml" type="spawnabletypes" />
	</ce>

If you are already using files to append your vanilla mission files, it should look something like this:

<ce folder="custom">
	<file name="some-other-types-file.xml" type="types" />
	<file name="some-other-events.xml" type="events" />
	<file name="Veh-OffroadHatchback-complete-with-M4A1-cfgspawnabletypes.xml" type="spawnabletypes" />
	<file name="some-other-messages.xml" type="messages" />
	<file name="some-other-globals.xml" type="globals" />
	</ce>

Save the file.

Upload where necessary.
	
Vailidate your edited files to check you haven't made any mistakes with https://www.xmlvalidation.com/

Restart your server & changes should start to take effect. How quickly will depend on the population of your server, as the old car spawns get replaced.

----------

Dominus vobiscum! scalespeeder

GOOD LUCK!