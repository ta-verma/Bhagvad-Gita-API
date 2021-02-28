![http://gita-api.herokuapp.com](https://img.shields.io/badge/-Bhagvadgita%20API-blueviolet.svg)

Bhagvadgita API
======

An API to get Bhagvadgita Sloaks.


## Table of Contents

* [Features](#features)
* [Usage](#api-usage)
* [Contributing](#contributing)

# Features

* Gita Sloaks
  * Broken down into chapter and Verse.
  * Get Sanskrit, Hindi and English Translations


# API Usage
### API Base URL: `http://gita-api.herokuapp.com/`

Result :
```json
{
	author: "Tarun Verma",
	author_url: "http://github.com/ta-verma",
	base_url: "gita-api.herokuapp.com",
	project_name: "Bhagvadgita API",
	project_url: "https://github.com/ta-verma/Bhagvadgita-API"
}
```

### GET: `/gita/chapter/<chapter_number>/verse/<verse_number>`
#### Example
Example usage: `GET http://gita-api.herokuapp.com/gita/chapter/1/verse/4`

Example result:
```json
{
english: "There are in this army, heroes wielding great bows, and equal in military prowess to Bhima and Arjuna: Yuyudhana (Satyaki) and Virata, and the maharatha (great chariot-rider) Drupada;",
hindi: "इस सेना में बड़े-बड़े धनुषों वाले तथा युद्ध में भीम और अर्जुन के समान शूरवीर सात्यकि और विराट तथा महारथी राजा द्रुपद...",
hindi_meaning: "(अत्रा) इस सेनामें (महेष्वासाः) बड़े-बड़े धनुषोंवाले (च) तथा (युधि) युद्धमें (भीमार्जुनसमाः) भीम और अर्जुनके समान (शूराः) शूर-वीर (युयुधानः) सात्यकि (च) और (विराटः) विराट (च) तथा (महारथः) महारथी (द्रुपदः) राजा द्रुपद",
sanskrit: "अत्र शूरा महेष्वासा भीमार्जुनसमा युधि | युयुधानो विराटश्च द्रुपदश्च महारथ: ॥4॥ "
}
```

# Contributing
Feel free to submit a pull request or an issue!


#### Note 1 : If the API goes down, please open a issue or comment on already existing one with the problem(s) that you are facing. This is the best way to let me know that the API is not working, avoid sending email. 

#### Note 2 : I will make this repositry public soon

