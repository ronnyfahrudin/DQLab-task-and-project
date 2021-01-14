library(dplyr)
library(corrplot)

chocolates2 <- chocolates %>% 
  select(atribut_sensoris) %>% 
  cor() %>% 
  corrplot(
    type = "upper",
    method = "square",
    diag = FALSE,
    addgrid.col = FALSE,
    order = "FPC", 
    tl.col = "gray30", 
    tl.srt = 30
  )
chocolates2
