Layout-ID: 1 (Without Signal Processing)
Layout-ID: 28 (With Signal Processing)


Add this to Clover Kext Patches:

                       <dict>
				<key>Comment</key>
				<string>AppleHDA ALC269 p1</string>
				<key>Find</key>
				<data>
				hBnUEQ==
				</data>
				<key>Name</key>
				<string>AppleHDA</string>
				<key>Replace</key>
				<data>
				aQLsEA==
				</data>
			</dict>
			<dict>
				<key>Comment</key>
				<string>AppleHDA ALC269 p2</string>
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