# Make SDL Symbolic link
ln -s /opt/homebrew/Cellar/sdl2/2.30.3/lib mac
ln -s /opt/homebrew/Cellar/sdl2/2.30.3/include/SDL2 SDL

## Add SDL lib links in lib/mac directory
ln -s /opt/homebrew/Cellar/sdl2_ttf/2.22.0/lib/libSDL2_ttf-2.0.0.dylib libSDL2_ttf-2.0.0.dylib
ln -s /opt/homebrew/Cellar/sdl2_image/2.8.2_1/lib/libSDL2_image-2.0.0.dylib libSDL2_image-2.0.0.dylib
ln -s /opt/homebrew/Cellar/sdl2_mixer/2.8.0/lib/libSDL2_mixer-2.0.0.dylib libSDL2_mixer-2.0.0.dylib


