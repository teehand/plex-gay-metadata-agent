<h1>plex-gay-metadata-agent</h1>
A Plex agent for fetching gay adult video metadata. https://forums.plex.tv/discussion/32922/adult-agents-for-gay-titles


<h1>INSTALLATION</h1>
1. Copy the Cockporn.bundle and any required site specific agents into the Plex Server plug-ins directory<br />
	<b>Mac:</b> ~/Library/Application Support/Plex Media Server/Plug-ins/<br />
	<b>QNAP:</b> /root/Library/Plex\ Media\ Server/Plug-ins/<br />
        <b>Windows:</b> Drive leter:\Program Files (x86)\Plex\Plex Media Server\Resources\Plug-ins-*******
2. Login to the web interface and open settings.
3. In Settings > Server > Agents select "Gay Adult" and check all required agents.
4. Create a new library or change the agent of an existing library to the "Gay Adult" agent.


<h1>HelixStudios.bundle</h1>
	NAMING CONVENTION:
		Enclosing directory: Any folder that starts with "Helix"
		Video Naming: Text title as displayed on Helix Studios website.

	KNOWN ISSUES
	- Limited ability to match titles with special characters in the name.
	- Unable to get metadata for bonus material from other sites.
	- Autoupdate may cause issues as it may cause a full metadata refresh when a new file is added.

<h1>Staxus.bundle</h1>
	NAMING CONVENTION:
		Enclosing directory: "Staxus"
		Video Naming: Text title or text of the title as displayed on Staxus website.

	KNOWN ISSUES
	- Limited ability to match titles with special characters in the name.
	- Unable to get metadata for bonus material from other sites.
	- Autoupdate may cause issues as it may cause a full metadata refresh when a new file is added.


<h1>NOTES</h1>
All metadata is downloaded by the end users personal Plex Media Server instance and no metadata is embedded in the agent bundle itself.
