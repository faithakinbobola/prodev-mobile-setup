# Scaffolding steps
1.  I moved to your parent project directory: cd prodev-mobile-setup
2. I initializec a new Expo project using the latest Expo Router template: npx create-expo-app@latest prodev-mobile-setup
3. I modified the Home Screen: Changed Welcome! to ** First App Created**
4. I ran this: `npx expo start`
5. When i ran `npm run reset-project`, I noticed the following:
Before Reset
- Custom changes were applied (Home screen showed First App Created).
- Dependencies and configurations were intact.

After Reset (npm run reset-project)
- The command cleaned cached files and reset the environment.
- Reverted the app back to its original scaffolded state (removing any custom modifications).
- The app/(tabs)/index.tsx file text returned to default Welcome!.
- It essentially gave a “fresh start” as if the project was just created again.