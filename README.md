# Egypt Governorates & Cities

JSON datasets of Egypt's governorates and cities/regions. Useful for address forms, database seeding, etc.

## Datasets

| File | Records | Contents |
| --- | ---: | --- |
| [governorates.json](governorates.json) | 27 | Governorates with Arabic and English names |
| [cities.json](cities.json) | 390 | Cities and regions linked to their governorates |


## Data examples

### Governorates

```json
{
  "id": 1,
  "name_ar": "القاهرة",
  "name_en": "Cairo"
}
```

### Cities and regions

```json
{
  "id": 133,
  "governorate_id": 1, // linked to the ID from the governorates dataset
  "name_ar": "مدينة نصر",
  "name_en": "Nasr City"
}
```

## License

This project is licensed under the [MIT License](LICENSE).
