# De Drie Theaterwetten

'De Drie Theaterwetten' is a video created by Richel Bilderbeek as an example for the course 'Stagecraft', module 'Movie'.

## Plot

A journalist reports that Richel Bilderbeek has won the Nobel price for stagecraft for his Three Laws of Stagecraft. He then interviews two theatre technicians, one specialized in light (at the left) and one specialized in sound (at the richt). After then interview, a gorgeous naked woman walks in.

# Conversion from WMV to OGV used

```
for x in *.wmv; do avconv -i "$x" -flags +ilme+ildct+alt "`basename "$x" .wmv`.ogv"; done
```

## License

![Licensed under CC-BY-NC_SA](License.png)

The movie is licensed under [CC-BY-NC-SA](https://creativecommons.org/licenses/by-nc-sa/3.0/legalcode), which is not yet explicitly visible in the movie.
