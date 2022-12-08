# BlurTransformation

This class will help to add bur effect on coil AsyncImage

Copy BlurTranformation.kt file to your repository and you are ready to engage!


```kotlin
//Usage example
AsyncImage(
  model = "https://avatars.githubusercontent.com/u/52178347?v=4",
  modifier = Modifier.size(100.dp),
  transfomations = listOf(
      BlurTransformation(
          scale = 0.5f,
          radius = 25
      )
  )
  /*your other params*/
)
```

## Note 
Also remember to add this dependencies to local build.gradle folder
```kotlin
//Coil 
implementation("io.coil-kt:coil:2.1.0")
implementation("io.coil-kt:coil-compose:2.1.0")
```
