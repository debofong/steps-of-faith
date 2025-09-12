Web app can be accessed at this link: https://debofong.github.io/steps-of-faith/

The data (saved routes, lap count, etc.) is not stored on GitHub servers. Instead, it is stored locally on each iPhone (or device) inside the browser’s localStorage.
Here’s what that means in practice:
When you click 💾 Save, your route is serialized (turned into JSON) and written to localStorage in Safari/Chrome.

Each device has its own separate localStorage. So if you save a route on your iPhone, it won’t show up on your laptop unless you export/import it.
The data persists across page reloads and app closes, but if you clear Safari cache or use “Clear Website Data,” it will be erased.
