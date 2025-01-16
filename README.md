# Green Wheels
A shared carpooling app. This application was developed as a project for the Web Information Technologies exam of the Computer Engineering degree program at Politecnico di Milano (IOL). This repository includes the backend, the frontend, and a core for shared code as submodules.

The app is designed to facilitate shared carpooling. Users can register and may optionally associate themselves with a community. Community members can view and offer rides within their community or see rides from users not affiliated with any community who offer rides to everyone. Similarly, users without a community can only see and offer rides to other unaffiliated users.

To offer rides, you must create a profile that lets others understand your preferences and seat availability. The app features an integrated chat for user communication, and drivers can be rated after completing a trip. When creating a ride, starting points and destinations can be conveniently selected from a map.

The app is designed to be accessible on all devices and is fully mobile-friendly.

The project is a POC and the miss most of the adva

## Usage

1. Clone the project.
```bash
git clone --recurse-submodules <repo-url>
```

2. Install the dependency:
```bash
npm i
```

3. Run:
```bash
npm run start:all
```
