# Dirty Rabbit Time Clock Display

Professional NFC time clock display page for Dirty Rabbit Coffee Shop employees.

## Live URL
**https://spicycarrot25.github.io/time-clock/**

## Usage
- **Clock In:** `?employee=DR001&status=in`
- **Clock Out:** `?employee=DR001&status=out`

## Features
- Spanish interface (¡Hola/¡Adiós!)
- 24-hour time format
- Madrid timezone
- Auto-close after 3 seconds
- Mobile-optimized for Android kiosk
- Dirty Rabbit brand colors (#cd202c, #f2ece1)

## Employees
- DR001: Maria
- DR002: Francisca  
- DR003: Juan

## Integration
This page is called by the n8n webhook after NFC clock events are processed through Supabase functions.