mutation {
    usersUpdateEmail(
        userId: "[USER_ID]",
        email: "email@example.com"
    ) {
        id
        createdAt
        updatedAt
        name
        password
        hash
        hashOptions
        registration
        status
        passwordUpdate
        email
        phone
        emailVerification
        phoneVerification
        prefs
    }
}