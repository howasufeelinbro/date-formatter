# date-formatter

> A package for formatting dates into the en-US format.

## Usage

```js
const { formatDate, logDate } = require('date-formatter')
const { MessageEmbed } = require('discord.js')

module.exports = {
    name: 'name-here',
    description: 'A test command using discord.js to showcase date-formatter.'

    run: async( bot, message, args ) => {
        let msg = message.channel.send(`Fetching...`)

        let m = `${formatDate(message.author.createdAt)}`

        msg.edit(m)
        // This will edit the message to display the date the user was created at

        console.log(`${logDate}`)
        // Logs the date in the console.
    }
}
```

## Installation

```
npm i date-formatter
```

## License

Apache 2.0

# date-formatter
