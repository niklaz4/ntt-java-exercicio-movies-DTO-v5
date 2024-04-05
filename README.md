<h1>Exercícios de Java NTT ACADEMY - DESIGN PATTERNS</h1>
<hr><br> 1) Criar DTO para usuário <br>2) Criar DTO para tratativa de resultado (Pode ser error ou sucesso)<br>
3) Criar método para popular o DTO (UserDTO) criado. Este método deve ter 2 parâmetros do tipo List (Ex: (final List<User> users, final List<UserDTO> userDTOS). Devemos implementar a seguinte regra dentro do método:
   <br> - Ler o conteúdo da List<User> - (Iterar lista)
    <br>- Salvar o resultado da iteração dentro da List<UserDTO>
4) Em seu projeto, adicione dependência modelmapper e commons-lang3<br>
<br>5) Implementar classe ModelMapperConfig
<br>No endpoint /user/id - converter o objeto User em UserDTO.class utilizando o modelMapper()  
