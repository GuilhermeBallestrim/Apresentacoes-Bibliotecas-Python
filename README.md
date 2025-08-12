# Apresentacoes-Bibliotecas-Python

## 1. Selenium  

**Descrição do Conteúdo Apresentado**  
O Selenium é uma API orientada a objetos voltada para automação de navegadores web, permitindo a execução de tarefas repetitivas de forma programática. Sua biblioteca em Python oferece métodos para controlar e interagir automaticamente com páginas, atendendo a diferentes necessidades de aplicativos web, incluindo localização de elementos e comparação de resultados esperados.  

A ferramenta é compatível com várias linguagens, como Java, C#, Python, Ruby, PHP, Perl e JavaScript, e oferece suporte para múltiplos navegadores e sistemas. Possui três componentes principais:  
- **Selenium WebDriver:** controle direto de navegadores reais.  
- **Selenium IDE:** gravação e reprodução de ações para testes rápidos.  
- **Selenium Grid:** execução de testes paralelos em várias máquinas.  

A instalação é feita via `pip install selenium`, e para uso é necessário um driver do navegador. O WebDriver Manager facilita a configuração desse driver automaticamente.  

**Principais Pontos Positivos**  
- Reduz erros e agiliza o trabalho de desenvolvedores/testadores.  
- Fornece feedback rápido e documenta casos de teste.  
- Permite execuções ilimitadas e suporta metodologias ágeis.  

**Limitações Apontadas**  
- Não suporta aplicações desktop.  
- Recursos limitados de relatórios e depuração.  
- Possível lentidão em grandes testes.  
- Curva de aprendizado elevada.  

**Exemplos de Métodos no Selenium (Python)**  
- `back()`: volta à página anterior.  
- `close()`: fecha a página atual.  
- `execute_script()`: executa JavaScript.  
- `refresh()`: atualiza a página.  
- `get_screenshot_as_file()`: salva captura de tela.  

**Aplicações Reais**  
Usado em empresas de tecnologia, especialmente em Qualidade de Software (QA), Desenvolvimento Web e DevOps, para automatizar testes e otimizar fluxos de trabalho.

**Aprendizado Obtido**  
Compreendi que o Selenium é uma ferramenta robusta e versátil para automação de testes em navegadores, e que o uso do WebDriver Manager simplifica muito sua configuração. Também aprendi que ele não se limita a Python, sendo amplamente adotado em diversas linguagens e ambientes.
