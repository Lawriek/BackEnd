# EmplManagerBackEnd
A simple NodeJs backend for retreving employees by position

## Setup

The project requires npm and NodeJs installed

## Build Project

1. Install typescript : `npm install -g typescript`
2. Install npx : `npm install npx`
3. Install project dependencies : `npm install`

## Launch Server
1. `npx ts-node src/server.ts`
2. Check localhost at port [8080](http://localhost:8080/)

## Services :
|Position | Url |
|----------------|---------|
|All Employees   |http://localhost:8080/allemployees|
|Juniors   |http://localhost:8080/juniors|
|Programmers   |http://localhost:8080/programmers|
|Engineers   |http://localhost:8080/engineers|
|Experts   |http://localhost:8080/experts|
|Managers   |http://localhost:8080/managers|