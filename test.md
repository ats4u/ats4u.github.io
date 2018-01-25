# Hello World

Hello world foo bar Hello world foo bar Hello world foo bar Hello world foo bar 
Hello world foo bar Hello world foo bar Hello world foo bar Hello world foo bar Hello world foo bar 
Hello world foo bar Hello world foo bar Hello world foo bar Hello world foo bar Hello world foo bar 

## FOO

* FOO
* BAR
* BUM

## Example of displaying htmlwidgets on a Github pages site

```{r}
# Source: http://www.htmlwidgets.org/showcase_plotly.html
library(plotly)
p <- ggplot(data = diamonds, aes(x = cut, fill = clarity)) +
            geom_bar(position = "dodge")
ggplotly(p)
```
