# dotnet-ios-issues

# Cache cleanup

1. Close VS
2. Delete the Build agent related “.checksum” files from %LOCALAPPDATA%\Temp\Xamarin\XMA\Remote in the Windows machine
3. Delete all files from ~/Library/Caches/Xamarin/XMA/Cache in the Mac machine
4. Delete the build agent related sub-folders from ~/Library/Caches/Xamarin/XMA/Agents/Build` in the Mac machine
5. Ensure no XMA process are running ps -A | grep XMA in the Mac machine. If there is any process running, kill it

# error MT1045: Failed to execute 'devicectl'

## Fix 1: Enable Developer Mode on device

On your Apple device, go to **Settings => Privacy & Security** and toggle the switch next to **Developer Mode**
