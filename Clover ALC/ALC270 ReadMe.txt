Layout-ID: 1 (Without Signal Processing)
Layout-ID: 28 (With Signal Processing)


Add this to Clover Kext Patches:

        <dict>
		<key>Comment</key>
		<string>AppleHDA ALC270 p1</string>
		<key>Find</key>
		<data>
		hBnUEQ==
		</data>
		<key>Name</key>
		<string>AppleHDA</string>
		<key>Replace</key>
		<data>
		cALsEA==
		</data>
	</dict>
	<dict>
		<key>Comment</key>
		<string>AppleHDA ALC270 p2</string>
		<key>Find</key>
		<data>
		hAjsEA==
		</data>
		<key>Name</key>
		<string>AppleHDA</string>
		<key>Replace</key>
		<data>
		AAAAAA==
		</data>
	</dict>