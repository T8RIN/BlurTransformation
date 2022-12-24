# BlurTransformation

This class will help to add blur effect on coil AsyncImage

Copy BlurTranformation.kt file to your repository and you are ready to engage!


```kotlin
//Usage example
val request = ImageRequest.Builder(context)
    .data("https://avatars.githubusercontent.com/u/52178347?v=4")
    .transformations(
        listOf(
           BlurTransformation(
               scale = 0.5f,
               radius = 25
           )
        ) 
    )
    .build()
        
AsyncImage(
  model = request,
  modifier = Modifier.size(100.dp)
  /*your other params*/
)
```

## Note 
Also remember to add this dependencies to local build.gradle folder
```kotlin
//Coil 
implementation("io.coil-kt:coil:2.2.2")
implementation("io.coil-kt:coil-compose:2.2.2")
```

## Find this repository useful? :heart:
Support it by joining __[stargazers](https://github.com/t8rin/blurtransformation/stargazers)__ for this repository. :star: <br>
And __[follow](https://github.com/t8rin)__ me for my next creations! 🤩

# License
```xml
Designed and developed by 2022 T8RIN

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```

