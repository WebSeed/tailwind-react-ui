### Text Inputs

Example:

```jsx
<Field hasHelp>
  <Label>Password</Label>
  <HelpText>
    Your password must be 8-20 characters long, contain letters and numbers, and
    must not contain spaces, special characters, or emoji.
  </HelpText>
  <TextInput name="password" type="password" />
</Field>
```

Disabled example:

```jsx
<Field disabled>
  <Label>Username</Label>
  <TextInput name="disabled" placeholder="Username" />
</Field>
```

Validation error example:

```jsx
<Field hasError>
  <Label>Username</Label>
  <TextInput name="invalid" placeholder="Username" />
  <ErrorText>Please enter a valid username</ErrorText>
</Field>
```
