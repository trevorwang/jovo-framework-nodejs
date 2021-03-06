# [Platform Specific Features](../) > Amazon Alexa

Learn more about Alexa specific features that can be used with the Jovo Framework.

* [Introduction to Alexa Specific Features](#introduction-to-alexa-specific-features)
* [Routing](#routing)
  * [Dialog Interface](#dialog-interface)
* [Data](#data)
  * [Shopping and To Do Lists](#shopping-and-to-do-lists)
  * [Location](#location)
* [Output](#output)
  * [Progressive Responses](#progressive-responses)
  * [Visual Output](#visual-output)
* [AudioPlayer Skills](#audioplayer-skills)

## Introduction to Alexa Specific Features

> Find an introduction to how Amazon Alexa works here: [Getting Started > Voice App Basics > Amazon Alexa](../../01_getting-started/voice-app-basics.md/#amazon-alexa).

You can access the `alexaSkill` object like this:

```javascript
let alexa = this.alexaSkill();
```


## Routing

This section provides an overview of Alexa specific features for routing. For the basic concept, take a look here: [App Logic > Routing](../../04_app-logic/01_routing).

### Dialog Interface

You can find more about dialog interface here: [Platform specifics > Amazon Alexa > Dialog Mode](./dialog.md).

## Data

This section provides an overview of Alexa specific features for user data. For the basic concept, take a look here: [App Logic > Data](../../04_app-logic/02_data).

### Shopping and To Do Lists

You can find more about lists here: [Platform specifics > Amazon Alexa > Lists](./lists.md)

### Location

Learn how to access your user's location data here: [Platform specifics > Amazon Alexa > Data](./data.md#location)

## Output

This section provides an overview of Alexa specific features for output. For the basic concept, take a look here: [App Logic > Output](../../04_app-logic/03_output).

### Progressive Responses

For responses that require long processing times, you can use progressive responses to tell your users that you are currently working on fulfilling their request.

Here is the official reference by Amazon: [Send the User a Progressive Response](https://developer.amazon.com/docs/custom-skills/send-the-user-a-progressive-response.html).

```javascript
this.alexaSkill().progressiveResponse(speech);
```

Find an example file here: [`indexProgressiveResponse.js`](../../../examples/alexa_specific/appProgressiveResponse.js).

### Visual Output

You can find out more about visual output here: [Platform specifics > Amazon Alexa > Visual](./visual.md)


## AudioPlayer Skills

You can find more about Jovo Audioplayer support here: [Platform specifics > Amazon Alexa > Audioplayer](./audioplayer.md).
