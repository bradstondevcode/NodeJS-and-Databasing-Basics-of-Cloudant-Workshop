# NodeJS and Databasing: Basics of IBM Cloudant Workshop

In this Worshop you will learn the basics of IBM Cloudant and how to create a NodeJS application that is powered by Cloudant NoSQL DB.

At the end of the workshop, participants will have learned the "Needs-to-Know" about Cloudant NoSQL DB and will have deployed a NodeJS and ReactJs application to the cloud driven by data housed in IBM Cloudant. 



## 🔥 Important Workshop First Steps 🔥

- ✅ Sign-up for FREE IBM Cloud Account:  [IBM Cloud Signup](https://ibm.biz/BdfqCq)
- ✅ Download/Clone ReactJS Workshop Starter Code: [Jellybean World React Github](https://github.com/bradstondevcode/jelly-bean-world-starter-code)
- ✅ Download/Clone Node.js Workshop Starter Code: [Jellybean World Node Github](https://github.com/bradstondevcode/jelly-bean-world-node-api)

## SPECIAL THANKS TO [Kyle Smith](https://www.linkedin.com/in/kyle-smith-67393b80/) for creating the Visual Design of Jellybean World!!

## 😁Please Take Survey After Class😁

This helps me to know how I can improve and make future workshops EVEN better!

Thanks in Advance!

[Short Post-Workshop Survey](https://ibm.biz/BdfqCf)

### Resources in Repo

- Workshop Slides
- Sample World JSON Files
- Step-by-Step Workshop Instructions (Coming Soon! 😎)

## Bonus Learning

[Deploying your first ReactJS application into the Cloud](https://ibm.biz/deploying-react-app-in-cloud-devto-bradstondev)

[Dockers and Dad Jokes: How to Containerize a ReactJS Application](https://ibm.biz/how-to-containerize-react-app-031821-bradstondev)

[Dockers and Dad Jokes: How to Containerize a NodeJS Application Using Docker](https://ibm.biz/blog-3-docker-dad-jokes-nodejs)

[Identity and Access Management (IAM) in the Cloud Basics: Why Devs Should Care](https://ibm.biz/IAM-in-the-cloud-devto-blog-bradstondev)

## Feel Free to Follow Me on Social Media

Twitter: [Bradston Dev](https://twitter.com/BradstonDev)
Dev.to: [@BradstonDev](https://dev.to/bradstondev)
Youtube: [Bradston YT](https://www.youtube.com/channel/UC6Ky8s71RP65akLb_XV1_OA)

## Check out My Unity3D Game using Cloudant NoSQL DB Live!

Use the password **"workshop2021"** to login. Username can be anything (preferably not your name). 

[![Amber](https://img.itch.zone/aW1hZ2UvMTgzMTA1Lzg1NjI0Mi5wbmc=/original/uvzIJy.png "Amber")](http://https://sleeping-zebu-games.itch.io/amber "Amber")

[Amber Itch.io Link](https://sleeping-zebu-games.itch.io/amber)

This game was created by myself and [Kyle Smith](https://www.linkedin.com/in/kyle-smith-67393b80/)

Amber uses Cloudant NoSQLDB to gain insights on how players play our game and how to make the game better. All information is completely anonymized and has **ZERO** personal information associated to it.

Here is an example of the data stored in our Cloudant NoSQL DB:

```javascript
{
  "_id": "BlueDog",
  "_rev": "61-a14509e70124dc2c5dafb979d0c0d567",
  "numOfDeaths": "60",
  "totalTimePlayed": "6741.18",
  "longestLifespan": "937.941",
  "currentPlayerLevel": {
    "pickaxeSkillLevel": "11",
    "pickaxeSpeedLevel": "4",
    "playerStaminaLevel": "7",
    "playerSpeedLevel": "10"
  },
  "boulderTypesDestroyed": {
    "talc": "245",
    "gypsum": "105",
    "graphite": "164",
    "calcite": "9",
    "flourite": "1",
    "apatite": "1",
    "feldspar": "0",
    "quartz": "0",
    "topaz": "0",
    "corundum": "1",
    "gold": "0",
    "diamond": "0",
    "amber": "0"
  },
  "numOfPickaxeSwings": "1376",
  "numOfRocksDestroyed": "526",
  "distanceTraveled": "47321.73",
  "totalAnimalsDefeated": "63",
  "deathsByBears": "0",
  "deathsByPigs": "4",
  "deathsByMonkeys": "2",
  "deathsByChickens": "0",
  "deathsByButterflies": "0",
  "deathsBySpiders": "0",
  "deathsByBirds": "0",
  "deathsByBats": "0",
  "deathsByWolves": "9",
  "deathsByTortoises": "0",
  "deathsByRoaches": "0",
  "deathsByLions": "3",
  "deathsByBees": "0",
  "deathsBySkyWorldBeings": "0",
  "deathsByWater": "30",
  "deathsByFire": "1",
  "didDefeatBigBadWolf": "true",
  "didDefeatBossMonkey": "true",
  "didDefeatMiniBossMonkey": "true",
  "didDefeatMurderBear": "false",
  "defeatedBears": "7",
  "defeatedPigs": "30",
  "defeatedMonkeys": "8",
  "defeatedChickens": "0",
  "defeatedButterflies": "0",
  "defeatedSpiders": "0",
  "defeatedBirds": "0",
  "defeatedBats": "0",
  "defeatedWolves": "7",
  "defeatedTortoises": "1",
  "defeatedRoaches": "0",
  "defeatedLions": "1",
  "defeatedBees": "8",
  "defeatedSkyWorldBeings": "0",
  "playerDeaths": [
    {
      "timeStamp": "228.2247",
      "deathBy": "Pig",
      "deathPosition": "(78.0, 329.3, -138.2)",
      "pickaxeSkillLevel": "2",
      "pickaxeSpeedLevel": "1",
      "playerStaminaLevel": "1",
      "playerSpeedLevel": "1",
      "lifespan": "228.0758"
    },
    {
      "timeStamp": "353.8926",
      "deathBy": "Pig",
      "deathPosition": "(99.8, 329.3, -129.0)",
      "pickaxeSkillLevel": "2",
      "pickaxeSpeedLevel": "1",
      "playerStaminaLevel": "1",
      "playerSpeedLevel": "2",
      "lifespan": "122.9558"
    },
    {
      "timeStamp": "544.2943",
      "deathBy": "Pig",
      "deathPosition": "(37.4, 329.3, -113.2)",
      "pickaxeSkillLevel": "5",
      "pickaxeSpeedLevel": "1",
      "playerStaminaLevel": "1",
      "playerSpeedLevel": "2",
      "lifespan": "187.5274"
    },
    {
      "timeStamp": "761.6025",
      "deathBy": "Water",
      "deathPosition": "(268.4, 310.1, -304.3)",
      "pickaxeSkillLevel": "5",
      "pickaxeSpeedLevel": "1",
      "playerStaminaLevel": "1",
      "playerSpeedLevel": "3",
      "lifespan": "214.5488"
    }
  ],
  "username": "BlueDog",
  "password": "pumpkinfb"
}

````