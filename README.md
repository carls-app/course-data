# course-data

For Carleton!

A sister repository to <https://github.com/StoDevX/course-data/>, which holds St. Olaf course data.

Each course in `courses/` looks like this:

```json
{
	"comments": [],
	"credits": 6.0,
	"department": "AFST",
	"id": "AFST 112.00",
	"instructors": [
		"Charisse E Burden-Stelly"
	],
	"number": "112.00",
	"offerings": {
		"locations": [
			"Leighton 426"
		],
		"times": [
			{
				"day": "Tu",
				"end": "4:55pm",
				"start": "3:10pm"
			},
			{
				"day": "Th",
				"end": "4:55pm",
				"start": "3:10pm"
			}
		]
	},
	"prerequisites": "None",
	"requirements": [
		{
			"code": "SI",
			"name": "Social Inquiry"
		},
		{
			"code": "WR2",
			"name": "Writing Rich 2"
		},
		{
			"code": "IDS",
			"name": "Intercultural Domestic Studies"
		}
	],
	"scnc": null,
	"size": {
		"registered": 24,
		"total": 30,
		"waitlist": 0
	},
	"status": "Open",
	"summary": null,
	"synonym": "49138",
	"tags": [
		{
			"code": "AFSTSI",
			"name": "Africana Stds Social Inquiry"
		},
		{
			"code": "POSI-PLI2",
			"name": "Philosophic & Legal Inq 2"
		},
		{
			"code": "SPECINTSOCTHGHT",
			"name": "Social Thought"
		}
	],
	"title": "Black Revolution on Campus"
}
```

This repository will soon be updated automatically each night (follow along in [issue #1](https://github.com/carls-app/course-data/issues/1)).

Currently, there is no way to bulk-download these courses. You can track the progress of that goal in [issue #2](https://github.com/carls-app/course-data/issues/2).
