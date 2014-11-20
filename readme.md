I expanded the functionality of the grading code by implementing additional interpretable functions. I also added comments to affected lines.

I also made an edit to the colorful theme to make it appear even brighter while also proposing an existentialist question while referencing a classic game. When you haven't started an assignment, the progress bar shows the Half-Life 2 missing texture, thus questioning whether or not, for the students who haven't started the webassign, it really exist?

![Integrader](https://raw.githubusercontent.com/bluepichu/integrader/master/public/images/logo-light.png)

## Description

Integrader is a project created to provide students and teachers with a streamlined method of completing and grading basic assignment types.  Grading can be tedious for teachers, and working on paper can be tedious for students; this solves both problems by allowing students to use the internet and by automating the grading system.

## Installation

### Requirements

Integrader requires Node.js and MongoDB to run.  It has only been tested with Node.js v.0.10.29 and MongoDB Standard 2.6.

### Running

To run Integrader, follow these steps:

1. Clone the repository.
2. Navigate to `/server`.
3. Run `npm install`
4. Run `mongod` to start the MongoDB database.
5. Run `node server/serv.js` to begin integrader.  This will open integrader `localhost:1337`.

## Release Notes

**Version 1.4**: Created teacher edit UI.  Fixed issues in `/assignment`.

- Version 1.4.0: Minimalistic `/edit` UI.  No labels.
- Version 1.4.1: Labeled UI and critical bugfix in `/assignment` for parsing symbolic inputs.

**Version 1.3**: Added "colorful" theme.  Fixed embed issues.  Created `/embed` to make it easier for students to join courses.

**Version 1.2**: Mobile devices now supported.

**Version 1.1**: Embeds now supported via `<embed>` and `<iframe>` tags.

**Version 1.0**: Stable for both student and teacher login.  Assignment creation must be done by typing in raw JSON assignment objects.

**Version 0.1**: Stable for student login only.  Course and assignment creation must be done by hand directly into the database.
