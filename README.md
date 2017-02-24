# De Drie Theaterwetten


'De Drie Theaterwetten' is a video created by Richel Bilderbeek as an example for the course 'Stagecraft', module 'Movie'.

Originally the movie was shot in WMV. Goals of this project is
 * to convert it to OGV without losing even more resolution
 * add the license to the movie


The conversion from WMV to OGV used:
<code>
for x in *.wmv; do avconv -i "$x" -flags +ilme+ildct+alt "`basename "$x" .wmv`.ogv"; done
</code>

## License

![Licensed under CC-BY-NC_SA](License.png)

The movie is licensed under [CC-BY-NC-SA](https://creativecommons.org/licenses/by-nc-sa/3.0/legalcode), which is not yet explicitly visible in the movie.
