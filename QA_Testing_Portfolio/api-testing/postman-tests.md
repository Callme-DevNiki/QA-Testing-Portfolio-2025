# API Testing Example

Endpoint tested:

GET /users

Test cases:

1 Verify status code is 200
2 Verify response time under 500ms
3 Verify response body contains user list

Postman Test Script:

pm.test("Status code is 200", function () {
pm.response.to.have.status(200);
});

pm.test("Response time < 500ms", function () {
pm.expect(pm.response.responseTime).to.be.below(500);
});