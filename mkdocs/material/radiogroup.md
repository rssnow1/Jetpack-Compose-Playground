!!! info
    This is the API of version dev09. Newer versions may have a different one

<p align="left">
  <img src ="../../images/material/radiogroup/RadioGroupExample.png" height=500 />
</p>

```kotlin
@Composable
fun RadioGroupSample() {
        val radioOptions = listOf("A", "B", "C")
        val (selectedOption, onOptionSelected) = state { radioOptions[1] }
        RadioGroup(
            options = radioOptions,
            selectedOption = selectedOption,
            onSelectedChange = onOptionSelected
        )
}
```

