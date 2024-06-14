# Hafez Faal Java Application

This is a Java application that uses an HTTPS API to display Hafez Faal (a traditional Persian practice of divination using the poetry of Hafez). The application comes with a graphical user interface (GUI) for an easy and pleasant user experience.

## Features

- Fetches Hafez Faal from an HTTPS API
- Displays the results in a user-friendly GUI
- Easy to use and lightweight

## API Usage

This application uses the Hafez Faal API provided at `https://faal.spclashers.workers.dev/api`. The API returns a random Faal from Hafez's poetry, which the application then displays.

### API Endpoint

- **URL**: `https://faal.spclashers.workers.dev/api`
- **Method**: `GET`
- **Response Format**: JSON

### Sample API Response

```json
{
  "faal": {
    "title": "فال حافظ",
    "content": "ای که دائم به خویشتن مغروری..."
  }
}
