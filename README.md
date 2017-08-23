## All you need to know Javascript functional development (Questions, Answers and Examples).
# Built in Angular 4 and firebase.

## Features

- Authentication w/ Router Guard
- Realtime Database CRUD Demo
- File Uploads to Firebase Storage Demo
- SASS + Bulma + FontAwesome
- Reactive Form Validation

## Usage

Create an account at https://firebase.google.com/

- `git clone https://github.com/oleglatypov/javascript-all-you-need-to-know.git firestarter`
- `cd javascript-all-you-need-to-know`
- `npm install`

#### environment.ts
```typescript
export const environment = {
    production: false,
    firebaseConfig: {
        apiKey: '',
        authDomain: '',
        databaseURL: '',
        projectId: '',
        storageBucket: '',
        messagingSenderId: ''
    }
  };
```
#### environment.prod.ts
```typescript
export const environment = {
    production: true,
    firebaseConfig: {
        apiKey: '',
        authDomain: '',
        databaseURL: '',
        projectId: '',
        storageBucket: '',
        messagingSenderId: ''
    }
  };
```

And finally `ng serve`

Anjoy, and create your own Library

Version-0.1
