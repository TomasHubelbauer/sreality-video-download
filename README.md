# SReality Video Download

1. Open the post page in your browser
2. Open the browser developer tools on the Network tab
3. Run the video player on the page
4. Find the `https://v…-a.sdn.cz/v_…/vmd/…` request (type `application/vnd.seznam-cz.spl+json`)
5. Find this path in the response object: `data.mp4.1140p.url`
6. Join together the URL using version from the request and the URL: `https://v…-a.sdn.cz/v_…/…`
7. Open that URL in a new tab in your browser
8. Right-click on the browser native video player and select Save Video As

This will result in an MP4 video file download.
The file is directly playable without any need for stitching or streaming handling.
