# JWT_tp
1-Test 1 — Login
POST /login
{
"username": "admin",
"password": "1234"
}
Renvoie un token

<img width="950" height="367" alt="image" src="https://github.com/user-attachments/assets/f7713d10-4763-4088-a3b0-a5a5460d8438" />


Test 2 — /profile sans token
GET /profile

Retourne 401 Unauthorized

<img width="1919" height="264" alt="image" src="https://github.com/user-attachments/assets/57d2da46-0782-4352-a459-66e337ab2361" />



Test 3 — /profile avec token
Authorization: Bearer <token>
→retourne 200 OK

<img width="1919" height="258" alt="image" src="https://github.com/user-attachments/assets/f4a17048-aade-4dc2-9c1a-0bd491d83cce" />


Test 4 — /me
Retourne payload JWT
→ bien vérifier sub, role, exp

<img width="1919" height="299" alt="image" src="https://github.com/user-attachments/assets/a640d086-b1a4-4b2b-ae81-b8d0bb1c0c3e" />


6. Ajouter un champ "email" dans le token JWT lors du login, puis

    le renvoyer dans /me,
    et l'afficher côté frontend.

<img width="982" height="419" alt="image" src="https://github.com/user-attachments/assets/306355f2-9c5c-443e-bf17-61c5f25ba395" />



