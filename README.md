# course-data

For Carleton!

A sister repository to <https://github.com/StoDevX/course-data/>, which holds St. Olaf course data.

## Usage
If you are interested in using the course data in another tool, it's hosted through Github on the `gh-pages` branch.

You can download it however you'd like, such as via curl. Assuming you want the 2016-Fall data in `json` format (aka the file `16FA.json`), you'd do:

	curl https://stodevx.github.io/course-data/terms/16FA.json

We have data from 1999-Fall through this year, whatever this year is, automatically updated from ENROLL once a day.

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
	"prerequisites": null,
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

This data is generated by the scripts in <https://github.com/carls-app/course-data-tools>.
