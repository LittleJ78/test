---
share: "true"
---

[[../Тех. документация/Структуры Данных Talent-Id|Структуры Данных Talent-Id]]

![[../assets/img/unnamed-1703568410236 1.png|unnamed-1703568410236 1]]

```json
{
  "canvas": {
    "version": "2.2.11",
    "width": 2000,
    "height": 2000,
    "scrollTop": 0,
    "scrollLeft": 0,
    "zoomLevel": 1,
    "show": {
      "tableComment": true,
      "columnComment": true,
      "columnDataType": true,
      "columnDefault": true,
      "columnAutoIncrement": false,
      "columnPrimaryKey": true,
      "columnUnique": false,
      "columnNotNull": true,
      "relationship": true
    },
    "database": "MySQL",
    "databaseName": "",
    "canvasType": "ERD",
    "language": "GraphQL",
    "tableCase": "pascalCase",
    "columnCase": "camelCase",
    "highlightTheme": "VS2015",
    "bracketType": "none",
    "setting": {
      "relationshipDataTypeSync": true,
      "relationshipOptimization": false,
      "columnOrder": [
        "columnName",
        "columnDataType",
        "columnNotNull",
        "columnUnique",
        "columnAutoIncrement",
        "columnDefault",
        "columnComment"
      ]
    },
    "pluginSerializationMap": {}
  },
  "table": {
    "tables": [
      {
        "name": "currency",
        "comment": "",
        "columns": [
          {
            "name": "currency_id",
            "comment": "",
            "dataType": "INTEGER",
            "default": "",
            "option": {
              "autoIncrement": false,
              "primaryKey": false,
              "unique": false,
              "notNull": true
            },
            "ui": {
              "active": false,
              "pk": false,
              "fk": false,
              "pfk": false,
              "widthName": 69.1962890625,
              "widthComment": 60,
              "widthDataType": 60,
              "widthDefault": 60
            },
            "id": "14ad5baa-3e6b-4e4a-9e79-1d2dcd72c1e8"
          },
          {
            "name": "status",
            "comment": "",
            "dataType": "string",
            "default": "",
            "option": {
              "autoIncrement": false,
              "primaryKey": false,
              "unique": false,
              "notNull": true
            },
            "ui": {
              "active": false,
              "pk": false,
              "fk": false,
              "pfk": false,
              "widthName": 60,
              "widthComment": 60,
              "widthDataType": 60,
              "widthDefault": 60
            },
            "id": "07f2051e-f32d-4942-b7ae-197afb8cffab"
          },
          {
            "name": "name",
            "comment": "",
            "dataType": "string",
            "default": "",
            "option": {
              "autoIncrement": false,
              "primaryKey": false,
              "unique": false,
              "notNull": true
            },
            "ui": {
              "active": false,
              "pk": false,
              "fk": false,
              "pfk": false,
              "widthName": 60,
              "widthComment": 60,
              "widthDataType": 60,
              "widthDefault": 60
            },
            "id": "a3dd9ef9-2fd6-43a4-96cb-ad7783dc5d2c"
          },
          {
            "name": "type",
            "comment": "",
            "dataType": "ENUM",
            "default": "",
            "option": {
              "autoIncrement": false,
              "primaryKey": false,
              "unique": false,
              "notNull": true
            },
            "ui": {
              "active": false,
              "pk": false,
              "fk": false,
              "pfk": false,
              "widthName": 60,
              "widthComment": 60,
              "widthDataType": 60,
              "widthDefault": 60
            },
            "id": "cebf45d9-f090-40ce-b215-973eebfa0fd7"
          }
        ],
        "ui": {
          "active": true,
          "left": 200.8,
          "top": 100.8,
          "zIndex": 154,
          "widthName": 60,
          "widthComment": 60
        },
        "visible": true,
        "id": "0047ff6e-b2ac-47a8-a2cd-9a46dfe1ae76"
      },
      {
        "name": "player_balance ",
        "comment": "",
        "columns": [
          {
            "name": "balanceId",
            "comment": "",
            "dataType": "INTEGER",
            "default": "",
            "option": {
              "autoIncrement": false,
              "primaryKey": false,
              "unique": false,
              "notNull": true
            },
            "ui": {
              "active": false,
              "pk": false,
              "fk": false,
              "pfk": false,
              "widthName": 60,
              "widthComment": 60,
              "widthDataType": 60,
              "widthDefault": 60
            },
            "id": "c9d2f7d2-e765-4a8f-aa69-c7c9f7dec2b7"
          },
          {
            "name": "playerId",
            "comment": "",
            "dataType": "INTEGER",
            "default": "",
            "option": {
              "autoIncrement": false,
              "primaryKey": false,
              "unique": false,
              "notNull": true
            },
            "ui": {
              "active": false,
              "pk": false,
              "fk": false,
              "pfk": false,
              "widthName": 60,
              "widthComment": 60,
              "widthDataType": 60,
              "widthDefault": 60
            },
            "id": "26b5a69f-a177-4d98-8236-1b101dc812e9"
          },
          {
            "name": "currencyId",
            "comment": "",
            "dataType": "INTEGER",
            "default": "",
            "option": {
              "autoIncrement": false,
              "primaryKey": false,
              "unique": false,
              "notNull": true
            },
            "ui": {
              "active": false,
              "pk": false,
              "fk": false,
              "pfk": false,
              "widthName": 62.68994140625,
              "widthComment": 60,
              "widthDataType": 60,
              "widthDefault": 60
            },
            "id": "28925438-a869-4e6a-9528-c6aee9b250fd"
          },
          {
            "name": "changeDate",
            "comment": "",
            "dataType": "TIMESTAMP",
            "default": "",
            "option": {
              "autoIncrement": false,
              "primaryKey": false,
              "unique": false,
              "notNull": true
            },
            "ui": {
              "active": false,
              "pk": false,
              "fk": false,
              "pfk": false,
              "widthName": 72.10986328125,
              "widthComment": 60,
              "widthDataType": 76.87060546875,
              "widthDefault": 60
            },
            "id": "ece87581-9445-4b8c-a9b1-478b03be4068"
          },
          {
            "name": "value",
            "comment": "",
            "dataType": "INTEGER",
            "default": "",
            "option": {
              "autoIncrement": false,
              "primaryKey": false,
              "unique": false,
              "notNull": true
            },
            "ui": {
              "active": false,
              "pk": false,
              "fk": false,
              "pfk": false,
              "widthName": 60,
              "widthComment": 60,
              "widthDataType": 60,
              "widthDefault": 60
            },
            "id": "5ccd9ede-10df-4744-911f-a54877591c60"
          },
          {
            "name": "reason_id",
            "comment": "",
            "dataType": "guid",
            "default": "",
            "option": {
              "autoIncrement": false,
              "primaryKey": false,
              "unique": false,
              "notNull": true
            },
            "ui": {
              "active": false,
              "pk": false,
              "fk": false,
              "pfk": false,
              "widthName": 60,
              "widthComment": 60,
              "widthDataType": 60,
              "widthDefault": 60
            },
            "id": "d3aaf8a1-1512-4c2d-bd4f-4026b6406fd6"
          }
        ],
        "ui": {
          "active": false,
          "left": 194.4,
          "top": 268,
          "zIndex": 96,
          "widthName": 93.787109375,
          "widthComment": 60
        },
        "visible": true,
        "id": "075574c0-d552-45d8-88ee-72c3a155c129"
      },
      {
        "name": "player_experience ",
        "comment": "",
        "columns": [
          {
            "name": "experienceId",
            "comment": "",
            "dataType": "INTEGER",
            "default": "",
            "option": {
              "autoIncrement": false,
              "primaryKey": false,
              "unique": false,
              "notNull": true
            },
            "ui": {
              "active": false,
              "pk": false,
              "fk": false,
              "pfk": false,
              "widthName": 76.43896484375,
              "widthComment": 60,
              "widthDataType": 60,
              "widthDefault": 60
            },
            "id": "f6b70187-c792-4f1c-990d-39457e2f09fe"
          },
          {
            "name": "playerId",
            "comment": "",
            "dataType": "INTEGER",
            "default": "",
            "option": {
              "autoIncrement": false,
              "primaryKey": false,
              "unique": false,
              "notNull": true
            },
            "ui": {
              "active": false,
              "pk": false,
              "fk": false,
              "pfk": false,
              "widthName": 60,
              "widthComment": 60,
              "widthDataType": 60,
              "widthDefault": 60
            },
            "id": "5c601266-0649-4d3f-a4b8-8a1b196980be"
          },
          {
            "name": "currencyId",
            "comment": "",
            "dataType": "INTEGER",
            "default": "",
            "option": {
              "autoIncrement": false,
              "primaryKey": false,
              "unique": false,
              "notNull": true
            },
            "ui": {
              "active": false,
              "pk": false,
              "fk": false,
              "pfk": false,
              "widthName": 62.68994140625,
              "widthComment": 60,
              "widthDataType": 60,
              "widthDefault": 60
            },
            "id": "324102ea-a60e-40d4-9f88-be9f904bb190"
          },
          {
            "name": "changeDate",
            "comment": "",
            "dataType": "TIMESTAMP",
            "default": "",
            "option": {
              "autoIncrement": false,
              "primaryKey": false,
              "unique": false,
              "notNull": true
            },
            "ui": {
              "active": false,
              "pk": false,
              "fk": false,
              "pfk": false,
              "widthName": 72.10986328125,
              "widthComment": 60,
              "widthDataType": 76.87060546875,
              "widthDefault": 60
            },
            "id": "b8a8dbbd-149b-4a8f-a76e-554e689fdf1f"
          },
          {
            "name": "value",
            "comment": "",
            "dataType": "INTEGER",
            "default": "",
            "option": {
              "autoIncrement": false,
              "primaryKey": false,
              "unique": false,
              "notNull": true
            },
            "ui": {
              "active": false,
              "pk": false,
              "fk": false,
              "pfk": false,
              "widthName": 60,
              "widthComment": 60,
              "widthDataType": 60,
              "widthDefault": 60
            },
            "id": "38ebc0cd-9d27-4bba-b406-ee1c2a5b1d23"
          }
        ],
        "ui": {
          "active": false,
          "left": 609.6,
          "top": 100.8,
          "zIndex": 144,
          "widthName": 111.84619140625,
          "widthComment": 60
        },
        "visible": true,
        "id": "4b9658b7-7d50-46ac-bb13-53af4dd0e7df"
      }
    ],
    "indexes": []
  },
  "memo": {
    "memos": []
  },
  "relationship": {
    "relationships": []
  }
}
```