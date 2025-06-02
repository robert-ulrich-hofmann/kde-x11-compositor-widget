# kde-x11-compositor-widget

KDE Widget to see and change the status of the compositor under X11. I use this to manually override the "Allow applications to block compositing" setting, which does not always work, especially when alt-tabbing repeatedly and fast in and out of fullscreen applications.
Under the hood this is a quick and dirty way of enabling / disabling the KWin compositor to circumvent the qdbus / qdbus6 problems in Plasma 6. 
