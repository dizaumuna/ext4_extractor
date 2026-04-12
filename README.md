# Low, Medium and High level supported ext4 extraction script.
It uses ext4.py parser which is in pys/ folder, and saves fs_config, filesystem_contexts and size of image.
You should use extractor.py to extract your images.
Use fspatch.py to patch your fsconfig to repack images (this is important).

# uses ULTRAMAN
means it will extract your images like superman.

# Why not using 7-zip-like tools to extract it?
If you do that, the only thing you will get is a bootloop. SeLinux & UID & GID's are important for Android so you need this script if you don't want your phone get bootloop

# the sog not approved yet
means not ready to use
