# Kevin Chromik Minihackathon Winter 2024

## 🚀 Live Demo  
[Check out the live demo here](TODO)

## 📦 Self-Hosting Options

You can host this app in two ways:

#### Using the Pre-Built Release
Download the latest build directly from the [Releases page](https://github.com/matthiashermsen/kevin-chromik-minihackathon-winter-2024/releases). Extract the files and place them on a webserver.

#### Running with Docker  
Pull the latest Docker image directly from the [Images page](https://github.com/matthiashermsen/kevin-chromik-minihackathon-winter-2024/pkgs/container/kevin-chromik-minihackathon-winter-2024)

### Configuration

The app requires two url search parameters

- `product-id`: The Infomaniak AI Tools product ID
- `token`: The Infomaniak token ( with AI Tools permissions )

Without these parameters, the app will not work as intended.

Example:

```
https://yourdomain.com?product-id=123&token=abc
```
