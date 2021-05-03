# fake-packages

Fake apt packages, created by `equivs`, to provide the dependency without the package itself being installed.

Current packages provided are:

 * `pulseaudio-dummy` (provides `pulseaudio`); WSLg provides pulseaudio services without requiring the actual package installed.
 * `xwayland-dummy` (provides `xwayland`); WSLg provides xwayland services without requiring the actual package installed.
 
 To install these packages most conveniently, [add the wsl-transdebian repository](https://arkane-systems.github.io/wsl-transdebian/).
 
