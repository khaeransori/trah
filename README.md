# Trah - Family Tree Web Application

Trah (pronounced [trah]; Javanese: ꦠꦿꦃ) is a web-based family tree application that allows users to visualize, manage, and share their family history. Inspired by the Javanese word for "family tree," Trah aims to connect generations by providing a user-friendly platform to create detailed family profiles and relationships.

## Features

- **User Management**: Register, login, and manage user profiles.
- **Interactive Family Trees**: Create and edit family trees with an intuitive drag-and-drop interface.
- **Family Member Profiles**: Add detailed information about each family member, including photos and life events.
- **Relationship Visualization**: View and edit relationships between family members.
- **Collaborative Editing**: Invite family members to contribute and edit trees collaboratively.
- **Privacy Controls**: Control who can view or edit your family trees.
- **Export and Import**: Export trees to PDF or import data from other genealogy tools.

## Technologies Used

- **Frontend**: Next.js, D3.js for visualization, Tailwind CSS for styling
- **Backend**: Nest.js
- **Database**: PostgreSQL, MongoDB, SQLite
- **Authentication**: Auth0
- **Hosting/Deployment**: Netlify for frontend, Heroku for backend

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

What things you need to install the software and how to install them:

```bash
node.js
npm
PostgreSQL or MongoDB or SQLite
Git
```

### Installing

A step by step series of examples that tell you how to get a development environment running:

1. Clone the repository:
   ```bash
   git clone https://github.com/khaeransori/trah.git
   ```
2. Install NPM packages for the server:
   ```bash
   cd trah
   yarn install
   ```
3. Install NPM packages for the client:
   ```bash
   cd packages/frontend
   yarn install
   ```
4. Run the server:
   ```bash
   cd ..
   yarn dev
   ```
5. Navigate to `http://localhost:3000` in your browser to view the application.

## Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/khaeransori/trah/tags).

## Authors

- **Khaer Ansori** - *Initial work* - [khaeransori](https://github.com/khaeransori)

See also the list of [contributors](https://github.com/khaeransori/trah/contributors) who participated in this project.

## License

This project is licensed under the GNU Affero General Public License (AGPL) v3.0 - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

- Hat tip to anyone whose code was used
- Inspiration
- etc