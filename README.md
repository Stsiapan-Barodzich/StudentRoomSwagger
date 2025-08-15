# StudentRoomSwagger

This repository contains an OpenAPI (Swagger) specification for a REST API to manage students and rooms.

The API provides the following functionality:

CRUD operations for students and rooms (create, read, update, delete).
Pagination for listing students and rooms (page and size parameters).
Search students by room (GET /rooms/{roomId}/students).
Move a student to another room (PATCH /students/{studentId}/move).
Student fields: id, name, sex, birthday, roomId.
Room fields: id, name.

The specification is written in OpenAPI 3.0.0 format and stored in YAML.

student_room_swagger.yaml: The OpenAPI specification for the API.

