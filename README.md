async (event, steps)=> {
const axios = require("axios")
const counter = $checkpoint + 1 || 1
const { data } = await axios({
  url: https://img.shields.io/static/v1?label=Profile-Views&message=${counter}&color=green,
})
$checkpoint = counter
$respond({
  status: 200,
  headers: {
    'Content-Type': 'image/svg+xml',
    'Cache-Control': 'max-age=0, no-cache, no-store, must-revalidate'
  },
  body: data,
}) 
}
