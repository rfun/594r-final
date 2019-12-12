library(tidyverse)
library(ggplot2)

library(plotly)


main_data_file = read_csv('data_monthly.csv', col_names=TRUE)

main_data_file <- main_data_file %>% rename(surface_runoff = "Surface Runoff Amount") 
main_data_file %>%
  plot_ly() %>%
  add_trace(x = ~DateTime, y = ~surface_runoff, type ="scatter", mode ="lines+markers")


