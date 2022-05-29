## Magnificent Cartographer: Schemas

Schemas used for Magnificent Cartographer objects.

To use these add these lines to your Visual Studio Code `settings.json`:

```json
{
    "yaml.schemas": {
        "https://mindflayer-vtt.github.io/magnificent-cartographer-schemas/magnificent-space.json": "*.magnificent.yml",
    },
    "json.schemas": [
        {
            "fileMatch": [
                "*.magnificent.json"
            ],
            "url": "https://mindflayer-vtt.github.io/magnificent-cartographer-schemas/magnificent-space.json"
        }
    ]
}
```