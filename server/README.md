# Proffy Backend

## How to start this project

Install the dependencies

`
yarn
yarn knex:migrate
`

And then run the project

`
yarn start
`

## Routes

### List Classes
GET: /classes

Query params:

- week_day: number (0 to 6)
- subject: string
- time: string (00:00)

### Create classes
POST: /classes

Body:

- name: string
- avatar: string
- whatsapp: string
- bio: string
- cost: number
- schedule: array
  - week_day: number (0 to 6)
  - from: string (00:00)
  - to: string (00:00)

### Get Connections
GET: /connections

### Create Connection
POST: /connections
