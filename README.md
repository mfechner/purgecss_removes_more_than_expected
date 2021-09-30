# Show problem: PurgeCSS removes to much
Clone repository and do a:
```
npm i
```

Then run the webserver with:
```
npm run start
```

Now access with a browser `http://localhost:8080/en/`.

You will see that the `LOGIN` button has a color.

Now execute:
```
npm run purge
```

Make sure you unregister the service worker in your browser, disable cache and reload.

You will see that the color of the button is gone, the background is not loaded anymore, maybe more problems.
