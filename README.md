# hdf-kotlin
Kotlin for HDF

```
fun readHdf(inputStream: InputStream): List<Group> {
    val reader = inputStream.bufferedHDFReader()
    val group = reader.readGroups()
    /* ... */
}
val dset = readHdf(/*Open a stream to HDF file*/)
```
Please star this repository if you want to use Kotlin for HDF.
