REEL TAB PWA package

This package contains the current REEL_TAB_COMPLETE.html wrapped as an installable PWA shell. It is not an Android APK/AAB yet.

Deploy the CONTENTS of this folder to an HTTPS static host (not the folder itself). Then test the site in Chrome and use PWABuilder to package the live URL for Android. Supabase remains the backend.

IMPORTANT: Do not change or expose the Supabase secret key. The HTML currently uses the publishable/anon key. Keep Supabase Row Level Security enabled.
