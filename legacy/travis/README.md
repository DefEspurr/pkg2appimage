# Generating AppImages as part of your Travis CI continuous builds

One way to do it is to write/adopt an `appimage.sh` script, which you run in the `script:` or `after_success:` section of your `.travis.yml`. Here are some especially well-annotated ones: https://github.com/search?q=%22For+more+information%2C+see+http%3A%2F%2Fappimage.org%2F%22&type=Code&utf8=%E2%9C%93

See these [real-world examples](https://github.com/search?l=yaml&q=%22appimage.sh%22+%22script%3A%22&ref=searchresults&type=Code&utf8=%E2%9C%93) for more examples on how projects have successfully integrated AppImage generation into their Travis CI pipelines. 

TODO: Write a generic `appimage.sh` that would make it trivially easy for any project to integrate; possibly using https://github.com/probonopd/linuxdeployqt. In the meantime, use one from the link above that matches your situation best.
