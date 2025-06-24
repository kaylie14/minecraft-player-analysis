# minecraft-player-analysis
dsci 100 project answering the question: "What player characteristics and behaviours are most predictive of subscribing to a game-related newsletter, and how do these features differ between various player types?"


library(tidyverse)
library(repr)
library(tidymodels)
library(tidyclust)

getwd()
list.files()
players <- read_csv("data/players (1).csv")
head(players)

sessions <- read_csv("data/sessions (1).csv")
head(sessions)
