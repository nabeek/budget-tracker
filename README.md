# Online/Offline Budget Tracker

## Motivation

This application utilizes progressive web application principles to allow for offline access and functionality. The user is able to add expenses and deposits to their budget with or without a connection. When entering transactions offline, pending transactions populate the total when brought back online.

## Usage

Online/Offline Budget Tracker is live [here](#).

## Screenshot

![budget-tracker](https://user-images.githubusercontent.com/4752937/86948433-5a7a0000-c10a-11ea-9f31-53f4a587d28d.gif)

## Tech Used

[Express](https://expressjs.com/)\
[MongoDB](https://www.mongodb.com/)\
[Mongoose](https://mongoosejs.com/docs/)\
[morgan](https://www.npmjs.com/package/morgan)

## Challenges

I attempted to use webpack for the development of this application, and while I was succesful in executing the generated bundles and manifest, there were issues with the IndexedDB. I'm not sure if this was an issue with caching or something else, but something I would like to explore further, with more time. 

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## Roadmap

- Styling is based on the provided code, but I prefer using a different framework
- Adding an option to delete a transaction could be helpful

## License

MIT © [nabeek](https://github.com/nabeek)