# metadata examples

## console log
```
<Event xmlns="urn:schemas-upnp-org:metadata-1-0/AVT/">
<InstanceID val="0">
<TransportState val="PLAYING"></TransportState>
<CurrentTransportActions val="PAUSE,STOP,SEEK"></CurrentTransportActions>
<CurrentTrackURI val="http://192.168.0.0:10246/MDEServer/7184F711-876D-4772-90D3-C5CA8800A068/1000.m4a"></CurrentTrackURI>
<CurrentTrackMetaData val="&lt;DIDL-Lite xmlns:dc=&quot;http://purl.org/dc/elements/1.1/&quot; xmlns:upnp=&quot;urn:schemas-upnp-org:metadata-1-0/upnp/&quot; xmlns=&quot;urn:schemas-upnp-org:metadata-1-0/DIDL-Lite/&quot; xmlns:microsoft=&quot;urn:schemas-microsoft-com:WMPNSS-1-0/&quot; xmlns:dlna=&quot;urn:schemas-dlna-org:metadata-1-0/&quot;&gt;&lt;item id=&quot;1000&quot; restricted=&quot;1&quot; parentID=&quot;0&quot; microsoft:cpId=&quot;{9A91DA6B-47D4-4B5C-9CD1-E1FE36E582DB}&quot; microsoft:trackId=&quot;1&quot;&gt;&lt;dc:title&gt;Days Of The Dance&lt;/dc:title&gt;&lt;dc:creator&gt;3 Daft Monkeys&lt;/dc:creator&gt;&lt;res size=&quot;12519539&quot; duration=&quot;0:06:01.465&quot; bitrate=&quot;32953&quot; protocolInfo=&quot;http-get:*:audio/mp4:DLNA.ORG_PN=AAC_ISO_320;DLNA.ORG_OP=01;DLNA.ORG_FLAGS=01700000000000000000000000000000&quot; sampleFrequency=&quot;44100&quot; bitsPerSample=&quot;16&quot; nrAudioChannels=&quot;2&quot; microsoft:codec=&quot;{00001610-0000-0010-8000-00AA00389B71}&quot;&gt;http://192.168.4.156:10246/MDEServer/7184F711-876D-4772-90D3-C5CA8800A068/1000.m4a&lt;/res&gt;&lt;res duration=&quot;0:06:01.465&quot; bitrate=&quot;176400&quot; protocolInfo=&quot;http-get:*:audio/L16;rate=44100;channels=2:DLNA.ORG_PN=LPCM;DLNA.ORG_OP=10;DLNA.ORG_CI=1;DLNA.ORG_FLAGS=01700000000000000000000000000000&quot; sampleFrequency=&quot;44100&quot; bitsPerSample=&quot;16&quot; nrAudioChannels=&quot;2&quot; microsoft:codec=&quot;{00000001-0000-0010-8000-00AA00389B71}&quot;&gt;http://192.168.4.156:10246/MDEServer/7184F711-876D-4772-90D3-C5CA8800A068/1000.m4a?formatID=00000033-A9AF-4584-84E2-55BFEF0A7D7E&lt;/res&gt;&lt;res duration=&quot;0:06:01.465&quot; bitrate=&quot;24000&quot; protocolInfo=&quot;http-get:*:audio/mpeg:DLNA.ORG_PN=MP3;DLNA.ORG_OP=10;DLNA.ORG_CI=1;DLNA.ORG_FLAGS=01700000000000000000000000000000&quot; sampleFrequency=&quot;44100&quot; nrAudioChannels=&quot;2&quot; microsoft:codec=&quot;{00000055-0000-0010-8000-00AA00389B71}&quot;&gt;http://192.168.4.156:10246/MDEServer/7184F711-876D-4772-90D3-C5CA8800A068/1000.mp3?formatID=0000003E-A9AF-4584-84E2-55BFEF0A7D7E&lt;/res&gt;&lt;upnp:class&gt;object.item.audioItem&lt;/upnp:class&gt;&lt;upnp:genre&gt;Folk&lt;/upnp:genre&gt;&lt;upnp:artist role=&quot;Performer&quot;&gt;3 Daft Monkeys&lt;/upnp:artist&gt;&lt;upnp:album&gt;The Antiquated And The Arcane&lt;/upnp:album&gt;&lt;upnp:originalTrackNumber&gt;5&lt;/upnp:originalTrackNumber&gt;&lt;dc:date&gt;2010-01-02&lt;/dc:date&gt;&lt;dc:description&gt;Amazon.com Song ID: 218821962&lt;/dc:description&gt;&lt;upnp:albumArtURI&gt;http://192.168.4.156:10246/MDEServer/7184F711-876D-4772-90D3-C5CA8800A068/1000.jfif?albumArt=0&lt;/upnp:albumArtURI&gt;&lt;upnp:albumArtURI dlna:profileID=&quot;JPEG_TN&quot;&gt;http://192.168.4.156:10246/MDEServer/7184F711-876D-4772-90D3-C5CA8800A068/1000.jpg?albumArt=0,formatID=00000025-A9AF-4584-84E2-55BFEF0A7D7E,width=160,height=160&lt;/upnp:albumArtURI&gt;&lt;desc id=&quot;artist&quot; nameSpace=&quot;urn:schemas-microsoft-com:WMPNSS-1-0/&quot; xmlns:microsoft=&quot;urn:schemas-microsoft-com:WMPNSS-1-0/&quot;&gt;&lt;microsoft:artistPerformer&gt;3 Daft Monkeys&lt;/microsoft:artistPerformer&gt;&lt;/desc&gt;&lt;desc id=&quot;Year&quot; nameSpace=&quot;urn:schemas-microsoft-com:WMPNSS-1-0/&quot; xmlns:microsoft=&quot;urn:schemas-microsoft-com:WMPNSS-1-0/&quot;&gt;&lt;microsoft:year&gt;2010&lt;/microsoft:year&gt;&lt;/desc&gt;&lt;/item&gt;&lt;/DIDL-Lite&gt;"></CurrentTrackMetaData>
</InstanceID>
</Event>
```

## Metadata unescaped:

```
<DIDL-Lite xmlns:dc="http://purl.org/dc/elements/1.1/" xmlns:upnp="urn:schemas-upnp-org:metadata-1-0/upnp/" xmlns="urn:schemas-upnp-org:metadata-1-0/DIDL-Lite/" xmlns:microsoft="urn:schemas-microsoft-com:WMPNSS-1-0/" xmlns:dlna="urn:schemas-dlna-org:metadata-1-0/"><item id="1000" restricted="1" parentID="0" microsoft:cpId="{9A91DA6B-47D4-4B5C-9CD1-E1FE36E582DB}" microsoft:trackId="1"><dc:title>Days Of The Dance</dc:title><dc:creator>3 Daft Monkeys</dc:creator><res size="12519539" duration="0:06:01.465" bitrate="32953" protocolInfo="http-get:*:audio/mp4:DLNA.ORG_PN=AAC_ISO_320;DLNA.ORG_OP=01;DLNA.ORG_FLAGS=01700000000000000000000000000000" sampleFrequency="44100" bitsPerSample="16" nrAudioChannels="2" microsoft:codec="{00001610-0000-0010-8000-00AA00389B71}">http://192.168.4.156:10246/MDEServer/7184F711-876D-4772-90D3-C5CA8800A068/1000.m4a</res><res duration="0:06:01.465" bitrate="176400" protocolInfo="http-get:*:audio/L16;rate=44100;channels=2:DLNA.ORG_PN=LPCM;DLNA.ORG_OP=10;DLNA.ORG_CI=1;DLNA.ORG_FLAGS=01700000000000000000000000000000" sampleFrequency="44100" bitsPerSample="16" nrAudioChannels="2" microsoft:codec="{00000001-0000-0010-8000-00AA00389B71}">http://192.168.4.156:10246/MDEServer/7184F711-876D-4772-90D3-C5CA8800A068/1000.m4a?formatID=00000033-A9AF-4584-84E2-55BFEF0A7D7E</res><res duration="0:06:01.465" bitrate="24000" protocolInfo="http-get:*:audio/mpeg:DLNA.ORG_PN=MP3;DLNA.ORG_OP=10;DLNA.ORG_CI=1;DLNA.ORG_FLAGS=01700000000000000000000000000000" sampleFrequency="44100" nrAudioChannels="2" microsoft:codec="{00000055-0000-0010-8000-00AA00389B71}">http://192.168.4.156:10246/MDEServer/7184F711-876D-4772-90D3-C5CA8800A068/1000.mp3?formatID=0000003E-A9AF-4584-84E2-55BFEF0A7D7E</res><upnp:class>object.item.audioItem</upnp:class><upnp:genre>Folk</upnp:genre><upnp:artist role="Performer">3 Daft Monkeys</upnp:artist><upnp:album>The Antiquated And The Arcane</upnp:album><upnp:originalTrackNumber>5</upnp:originalTrackNumber><dc:date>2010-01-02</dc:date><dc:description>Amazon.com Song ID: 218821962</dc:description><upnp:albumArtURI>http://192.168.4.156:10246/MDEServer/7184F711-876D-4772-90D3-C5CA8800A068/1000.jfif?albumArt=0</upnp:albumArtURI><upnp:albumArtURI dlna:profileID="JPEG_TN">http://192.168.4.156:10246/MDEServer/7184F711-876D-4772-90D3-C5CA8800A068/1000.jpg?albumArt=0,formatID=00000025-A9AF-4584-84E2-55BFEF0A7D7E,width=160,height=160</upnp:albumArtURI><desc id="artist" nameSpace="urn:schemas-microsoft-com:WMPNSS-1-0/" xmlns:microsoft="urn:schemas-microsoft-com:WMPNSS-1-0/"><microsoft:artistPerformer>3 Daft Monkeys</microsoft:artistPerformer></desc><desc id="Year" nameSpace="urn:schemas-microsoft-com:WMPNSS-1-0/" xmlns:microsoft="urn:schemas-microsoft-com:WMPNSS-1-0/"><microsoft:year>2010</microsoft:year></desc></item></DIDL-Lite>
```


## Metadata formated

```
<?xml version="1.0" encoding="UTF-8"?>
<DIDL-Lite xmlns="urn:schemas-upnp-org:metadata-1-0/DIDL-Lite/" xmlns:dc="http://purl.org/dc/elements/1.1/" xmlns:dlna="urn:schemas-dlna-org:metadata-1-0/" xmlns:microsoft="urn:schemas-microsoft-com:WMPNSS-1-0/" xmlns:upnp="urn:schemas-upnp-org:metadata-1-0/upnp/">
   <item id="1000" restricted="1" parentID="0" microsoft:cpId="{9A91DA6B-47D4-4B5C-9CD1-E1FE36E582DB}" microsoft:trackId="1">
      <dc:title>Days Of The Dance</dc:title>
      <dc:creator>3 Daft Monkeys</dc:creator>
      <res size="12519539" duration="0:06:01.465" bitrate="32953" protocolInfo="http-get:*:audio/mp4:DLNA.ORG_PN=AAC_ISO_320;DLNA.ORG_OP=01;DLNA.ORG_FLAGS=01700000000000000000000000000000" sampleFrequency="44100" bitsPerSample="16" nrAudioChannels="2" microsoft:codec="{00001610-0000-0010-8000-00AA00389B71}">http://192.168.4.156:10246/MDEServer/7184F711-876D-4772-90D3-C5CA8800A068/1000.m4a</res>
      <res duration="0:06:01.465" bitrate="176400" protocolInfo="http-get:*:audio/L16;rate=44100;channels=2:DLNA.ORG_PN=LPCM;DLNA.ORG_OP=10;DLNA.ORG_CI=1;DLNA.ORG_FLAGS=01700000000000000000000000000000" sampleFrequency="44100" bitsPerSample="16" nrAudioChannels="2" microsoft:codec="{00000001-0000-0010-8000-00AA00389B71}">http://192.168.4.156:10246/MDEServer/7184F711-876D-4772-90D3-C5CA8800A068/1000.m4a?formatID=00000033-A9AF-4584-84E2-55BFEF0A7D7E</res>
      <res duration="0:06:01.465" bitrate="24000" protocolInfo="http-get:*:audio/mpeg:DLNA.ORG_PN=MP3;DLNA.ORG_OP=10;DLNA.ORG_CI=1;DLNA.ORG_FLAGS=01700000000000000000000000000000" sampleFrequency="44100" nrAudioChannels="2" microsoft:codec="{00000055-0000-0010-8000-00AA00389B71}">http://192.168.4.156:10246/MDEServer/7184F711-876D-4772-90D3-C5CA8800A068/1000.mp3?formatID=0000003E-A9AF-4584-84E2-55BFEF0A7D7E</res>
      <upnp:class>object.item.audioItem</upnp:class>
      <upnp:genre>Folk</upnp:genre>
      <upnp:artist role="Performer">3 Daft Monkeys</upnp:artist>
      <upnp:album>The Antiquated And The Arcane</upnp:album>
      <upnp:originalTrackNumber>5</upnp:originalTrackNumber>
      <dc:date>2010-01-02</dc:date>
      <dc:description>Amazon.com Song ID: 218821962</dc:description>
      <upnp:albumArtURI>http://192.168.4.156:10246/MDEServer/7184F711-876D-4772-90D3-C5CA8800A068/1000.jfif?albumArt=0</upnp:albumArtURI>
      <upnp:albumArtURI dlna:profileID="JPEG_TN">http://192.168.4.156:10246/MDEServer/7184F711-876D-4772-90D3-C5CA8800A068/1000.jpg?albumArt=0,formatID=00000025-A9AF-4584-84E2-55BFEF0A7D7E,width=160,height=160</upnp:albumArtURI>
      <desc id="artist" nameSpace="urn:schemas-microsoft-com:WMPNSS-1-0/">
         <microsoft:artistPerformer>3 Daft Monkeys</microsoft:artistPerformer>
      </desc>
      <desc id="Year" nameSpace="urn:schemas-microsoft-com:WMPNSS-1-0/">
         <microsoft:year>2010</microsoft:year>
      </desc>
   </item>
</DIDL-Lite>
COPY TO CLIPBOARD	 SELECT ALL
```
