Docs coming soon ... _in the meantime file an issue if you have any question_

---

The idea of all class names (_well more and less_) are picking the first letter of each word of css proprty, e.g `background-size`, and css value, e.g `cover` separated by dash, for example:
- `background-size: cover` becomes `bs-c`
- `background-image: none` becomes `bi-n`

Of course there are some exceptions, for example we have `background-size: cover` and `background-size: contain`, based on above guideline the class name for both is `bs-c` which is not acceptable, so I apply the above guideline to `background-size: cover`, because it's more common, and use the full value name for less common one, so `background-size: contain` becomes `bs-contain`. there are some other exceptions which will be covered in the documentation.
