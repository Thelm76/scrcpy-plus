<template>
    <div>

        <section>
            <v-card-title>
                <back />
                Changelog
            </v-card-title>
        </section>

        <section>
            <h3>2.0.0</h3>
            <ul>
                <li>Rewrite update notice modal to banner</li>
                <li>Add more icons to buttons</li>
                <li>Cache SCRCPY and ADB versions so the homepage loads faster</li>
                <li>Rewrite start error notice modal to banner</li>
                <li>Improve the UI for the file manager</li>
                <li>Remove "Resource Monitor" from tools</li>
                <li>Restyle all buttons</li>
                <li>Various UI tweaks</li>
                <li>Program now knows when SCRCPY is running</li>
                <li>Upgrade Dependencies</li>
                <li>Add settings menu back</li>
                <li>Fix MacOS window options displaying over title bar</li>
                <li>Rework "Device" section</li>
                <li>Remove "ADB Quick Actions" section</li>
            </ul>
        </section>

        <section>
            <h3>1.5.2</h3>
            <ul>
                <li>Upgrade Dependencies</li>
            </ul>
        </section>

        <section>
            <h3>1.5.1</h3>
            <ul>
                <li>Clean up some code</li>
                <li>Improve app stability</li>
                <li>Add "Restart App" button when app fails to start properly</li>
                <li>Remove app settings (sorry for feature loss, i hate to do that but the code was so annoying to maintain for something useless imho)</li>
                <li>Remove fingerprint from "Device" information section</li>
                <li>Add icons to "Device" information section</li>
                <li>Improve rendering of "Device", "SCRCPY Settings", "Tools" and "ADB Quick Actions" sections</li>
                <li>Change "Build" to "Build Number" under the "Device"</li>
            </ul>
        </section>

        <section>
            <h3>1.5.0</h3>
            <ul>
                <li>Slight UI Tweaks</li>
                <li>Disable Resource Monitor tool since it only worked on older samsung devices</li>
                <li>Move Tools and ADB Quick Commands next to eachother as per the request of reddit/u/aroonz</li>
                <li>Fix errors not showing on some devices when starting SCRCPY</li>
                <li>Change how SCRCPY flags are rendered for better performance and style</li>
                <li>Change how the file manager renders list items</li>
                <li>Change how icons are rendered</li>
                <li>Add settings page</li>
                <li>Add the ability do disable sections of the app in settings</li>
                <li>Change default window bounds</li>
                <li>Adjust bounding on wireless connecting success screen</li>
            </ul>
        </section>

        <section>
            <h3>1.4.1</h3>
            <ul>
                <li>Minor language tweaks / better action description</li>
                <li>Improve device recognition time</li>
                <li>Fix memory leak in device detection</li>
                <li>Refactor how the loading wheel is shown</li>
                <li>Show the loading wheel when connecting to a new device</li>
                <li>App automatically detects your OS and builds for it :)</li>
                <li>Add basic resource monitor</li>
                <li>Fixes for Linux & MacOS builds</li>
            </ul>
        </section>

        <section>
            <h3>1.4.0</h3>
            <ul>
                <li>Refactor the build process for the app</li>
                <li>The app now fully uninstalls itself properly if you use the built in uninstaller after using the "installer" build</li>
                <li>Bump Electron from 16.2.8 to ^19.0.7</li>
                <li>Huge performance improvements</li>
                <li>Refactor the `execute` command in the backend</li>
                <li>Add file manager</li>
            </ul>
        </section>

        <section>
            <h3>1.3.3</h3>
            <ul>
                <li>Fix device not being recognized when plugged in</li>
            </ul>
        </section>

        <section>
            <h3>1.3.2</h3>
            <ul>
                <li>Make the back button more uniform throughout the app</li>
                <li>Add new "Coming Soon" tool "Resource Monitor"</li>
                <li>Add building guide to the github (BUILDING.md)</li>
                <li>Major device polling improvements</li>
                <li>Fix spelling error (im human too)</li>
                <li>Finally add a bitrate slider after MANY requests</li>
            </ul>
        </section>

        <section>
            <h3>1.3.1</h3>
            <ul>
                <li>Add new section: "Tools"</li>
                <li>Add tool "Package Manager"</li>
                <li>Rework the "Back Button"</li>
                <li>Fix issue where wireless connection sometimes crashes the app</li>
            </ul>
        </section>

        <section>
            <h3>1.3.0</h3>
            <ul>
                <p class="accent--text">In this update, I wanted to return some of the awesome UI/UX to the app that it used to have. Everything was getting too cluttered and hard to navigate for new users, so I took some time to clean it up and restore it to the "good ol' days".</p>
                <li>Update "ADB Quick Actions" to fit the rounded theme of the app</li>
                <li>Changed order of "ADB Quick Actions" buttons</li>
                <li>Add "Advanced" SCRCPY Settings</li>
                <li>Improved error handling</li>
                <li>Add custom scrollbar to fit app theme</li>
                <li>Pressing 'enter' in the wireless setup now pairs/connects to the device</li>
                <li>Fix inputting nothing in the wireless setup causing the app to crash</li>
                <li>Brand new title bar to fit the app theme!</li>
                <li>Set minimum window width</li>
                <li>Automatically continue back to home page after wireless pairing setup</li>
            </ul>
        </section>

        <section>
            <h3>1.2.1</h3>
            <ul>
                <li>Added automatic update notification</li>
                <li>Bump SCRCPY Version (1.23 -> 1.24)</li>
            </ul>
        </section>

        <section>
            <h3>1.2.0</h3>
            <ul>
                <li>Refactored some of the app to be more modular</li>
                <li>Dynamically get the installed version of SCRCPY</li>
                <li>Dynamically get the installed version of ADB</li>
                <li>Minor UI Tweaks</li>
                <li>Multi-platform / Linux Support</li>
                <li>Some Bug Fixes</li>
                <li>Take 'Wireless Connection' Development Warning Away</li>
            </ul>
        </section>

        <section>
            <h3>1.1.2</h3>
            <ul>
                <li>Added wireless pairing gui</li>
                <li>Added support for ADB over Wi-Fi</li>
                <li>(KNOWN BUG) having multiple devices connected crashes the app</li>
            </ul>
        </section>

        <section>
            <h3>1.1.1</h3>
            <ul>
                <li>Fix error being thrown when closing the SCRCPY window</li>
                <li>Increased device information/recognition polling rate 8x</li>
                <li>Optimized device recognition to use less system resources</li>
                <li>Fixed causing some devices to lag badly while having the main window open</li>
            </ul>
        </section>

        <section>
            <h3>1.1.0</h3>
            <ul>
                <li>Bump SCRCPY Version (1.22 -> 1.23)</li>
                <li>General UI layout improvements</li>
                <li>Huge memory optimization</li>
                <li>Added loading icon on the 'Start SCRCPY' button to prevent the user from opening multiple SCRCPY instances</li>
                <li>Changed "Device Not Found" notice</li>
                <li>When a device isn't detected, all device options are now hidden</li>
                <li>Added SCRCPY Option: "--lock-video-orientation"</li>
            </ul>
        </section>

        <section>
            <h3>1.0.4</h3>
            <ul>
                <li>Improved error handling: Errors now show a popup box</li>
                <li>Added SCRCPY Option: "--always-on-top"</li>
                <li>Added SCRCPY Option: "--prefer-text"</li>
                <li>Added SCRCPY Option: "--raw-key-events"</li>
                <li>Added SCRCPY Option: "--no-key-repeat"</li>
            </ul>
        </section>

        <section>
            <h3>1.0.3</h3>
            <ul>
                <li>Wrapped text / Text doesn't leave the window without giving the option to scroll</li>
                <li>Fixed a lot of issues with running or using ADB on the previous version</li>
            </ul>
        </section>

        <section>
            <h3>1.0.2</h3>
            <ul>
                <li>Removed unused files</li>
                <li>Moved SCRCPY files to /resources instead of /bin as per a standard Electron application</li>
                <li>Update windows binary information</li>
                <li>Added optional windows installer file</li>
                <li>General software cleanup</li>
            </ul>
        </section>
        
        <section>
            <h3>1.0.1</h3>
            <ul>
                <li>Added changelog</li>
                <li>Added support for more devices in the "Devices" section</li>
                <li>Changed a few backend things</li>
                <li>Generally smoothed out the experience</li>
            </ul>
        </section>

        <section>
            <h3>1.0</h3>
            <ul>
                <li>Made the app :)</li>
            </ul>
        </section>

    </div>
</template>
