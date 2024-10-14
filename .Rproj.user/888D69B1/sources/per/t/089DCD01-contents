library(tidyverse)
library(readxl)
library(rio)

data <- import("input/data.xlsx", na = "NA")

clean_data <- data %>% 
  slice(-c(23,48))

# Save in RDS format
# saveRDS(clean_data, file = "input/clean_data.rds")

# Use rio
export(clean_data, "input/clean_data.rds")
