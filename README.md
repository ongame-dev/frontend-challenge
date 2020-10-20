# Ongame Front End Challenge

## Hello
This is the Ongame front-end challenge. It is a generic example of what your daily life will be like.

## Prerequisites
You should to know GIT, HTML, CSS and JavaScript.

## Getting Started
Fork this repository, it needs to stay on GitHub, available for everyone.

## The Challenge
You will create the example-x.png where you will display the items available for players to redeem.

Items will be loaded by GET [this json](https://br.ongame.net/api/challenge/items/)

Clicking on the redeem button, you will send POST to [this URL](https://br.ongame.net/api/challenge/item/redeem/) with this data:

```json
{
  "item_id": 1,
}
```

Be creative and organized. Each line will be evaluated.
