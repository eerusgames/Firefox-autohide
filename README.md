# Firefox-autohide

Setup:
1. Install the Sidebery extension version 5.0 or above: https://github.com/mbnuqw/sidebery
2. In Sidebery settings:
    a. Set the title preface must as "[🦊] " (without quotes).
        This is used by CSS rules below to identify when Sidebery is active.
    b. Copy and paste the "Sidebery Stylesheet" section below as a custom
        Sidebar CSS in Sidebery's "Styles Editor".
3. Go to about:support -> Click on "Profile Folder" -> "Open Folder"
4. Create a sub-folder named "chrome" -> Paste the "userChrome.css" in the chrome folder.
5. Go to about:flags -> `toolkit.legacyUserProfileCustomizations.stylesheets` to TRUE.
6. Restart Firefox ( about:restartrequired ).
