const express = require('express')

const app = express()

app.get('/', (req, res) => {
    res.send('hello')
})

app.get('/callback',(req, res) => {
    res.send('Welcome') #here word welcom will display in browser when authorized.
})

app.listen(3000,() => {
    console.log('we are running on port 3000') #show in terminal when running.
})
