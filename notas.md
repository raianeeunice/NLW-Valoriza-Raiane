/**
 * GET => Buscar uma informação
 * POST => Inserir uma informação
 * PUT => Alterar umna informação
 * DELETE => Remover um dado
 * PATCH => Alterar uma informação específica 
 */

/**
 * TIPOS DE PARÂMETROS
 * Routes Params => http://localhost:3000/produtos/765847293750
 * Query Params => http://localhost:3000/produtos?name=monitor&description=monitorfullhd&
 * 
 * Body Params => {
 *  "name": "monitor",
 *  "description": "monitor full hd"
 * }
 */
app.get("/test", (request, response) => {
    // Request => Entrando
    // Response => Saindo
    return response.send("Olá NLW");
})

app.post("/test", (request, response) => {
    return response.send("Olá Post");
})


- server ->   controller  -> SERVICE  -> Repositório -> BD