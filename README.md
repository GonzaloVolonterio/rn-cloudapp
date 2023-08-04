# CloudApp

## React Native File Upload with Expo to Supabase Storage

This app is using the expo-router and Supabase to upload files to Supabase Storage.

Routes are protected by Supabase Auth.

### Configuration

```
Make sure to include your own Supabase keys inside the config .env 

Also create a new bucket files inside Supabase Storage, and use the create-policy.sql
to create a policy that allows users to upload files only to their own folder inside the bucket.

```

### Built With

```
Typescript
Expo
Expo-router
React-Native
Supabase
Supabase Auth
```

### Clone repo 🔧

```
https://github.com/GonzaloVolonterio/rn-cloudapp

```
### Install🔧

```
npm install

npx expo start or npm start

```


### .env

```

EXPO_PUBLIC_SUPABASE_URL=
EXPO_PUBLIC_SUPABASE_ANON_KEY=

```

Examples App

![mycloupapp](https://github.com/GonzaloVolonterio/rn-cloudapp/assets/64506662/2ff973df-017b-4dac-8b21-528e6939d65a)





