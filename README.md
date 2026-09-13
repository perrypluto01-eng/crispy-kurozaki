# crispy-kurozaki
const express = require('express'); const app = express(); const path = require('path');  app.use(express.json()); app.use(express.static(__dirname));  // Default button options sent with fallback responses const defaultOptions = ['Pricing', 'Hours', 'Contact Support'];  // Rule database for custom bot respons
