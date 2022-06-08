# Anastasiya Ionikava

## Front-end developer

***

### Contacts and links

__Telegram:__   https://t.me/nastaion


__E-mail:__     nastya.ionicova@gmail.com


__GitHub:__     https://github.com/nastaion

***

### Short bio

I was born in Minsk on 27.08.1996.

I graduated from the Faculty of Philology of Belarusian State University with a Bachelor's degree in Slavic Philology.

After graduating from the university, I worked as a Belarusian language teacher for 2 years in one of the secondary schools in Minsk. During this period, I managed to act as a volunteer and teacher at the International Summer School of Belarusian Studies (2017).

In 2019, I started my career in marketing and project management: I worked as a marketer for the Russian holiday and entertainment franchise Fort Family (now Rublev Family). Currently and as a project manager at Vinst marketing agency.

Since 2020, I have been working closely with the Northern Lights Nordic-Baltic Film Festival in Belarus as a Zoom Manager. My tasks include preparing, technical support, broadcasting live events, recording, post-production control and publication of recorded events on the festival's industrial platform.

***

### Skills

__Front-end__

+ HTML (basic)

+ CSS (basic)

+ JavaScript (basic)

__Back-end__

+ PHP (basic)

__Data Science__

+ R (basic)

***

### Education

1. BSU (Bachelor's degree in Slavic Philology).
2. HTML academy (Introduction to web development).
3. Hexlet (JavaScript Setup).

***

### Examples of my code

#### JavaScript

```text
function multiply(a,b){
a * b
}
```

#### R

```text
priceplot <- function(data, ticker, normalise=F){
    
  if (normalise) {
      data  <- data %>% spread(stock, close) 
      
      for (it in c(2:17)){
        data[it] <- (data[it])/(data[1,it])*100
        }
      
      data <- data %>% gather(key = stock, value =close, -date)
    }
    
     data %>%  
       filter(stock %in% ticker) %>%
       ggplot(aes(x = date, y = close, colour = stock)) +
       geom_line() +
       labs (title = ticker)
} 
```

***

### Languages

__English__     (A2)


__Belarussian__ (native)


__Russian__     (C1)


__Polish__      (A2)
