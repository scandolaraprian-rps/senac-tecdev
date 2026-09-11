O **Definition of Done (DoD)** — ou *Definição de Pronto* — é um acordo coletivo e explícito estabelecido pela equipe de desenvolvimento sobre o que significa uma tarefa (história de usuário ou funcionalidade) estar 100% concluída.

Enquanto os *critérios de aceite* definem se uma funcionalidade específica atende ao que o usuário pediu, a DoD define a **qualidade padrão** que *todos* os itens do projeto devem cumprir antes de serem considerados prontos para ir para produção. Ela evita o famoso "funciona na minha máquina".

---

### Checklist Prática: 5 Itens Essenciais da DoD

1. **Código Revisado (Code Review):**
* O código foi submetido via Pull Request e revisado/aprovado por pelo menos outro desenvolvedor da equipe para garantir boas práticas e padronização.


2. **Testes Executados com Sucesso:**
* Todos os testes automatizados (unitários e de integração) passam sem erros, e novos testes foram criados para cobrir a nova funcionalidade.


3. **Critérios de Aceite Validados:**
* A funcionalidade atende rigorosamente a todas as regras de negócio e requisitos definidos no planejamento (sem pendências ou "gambiarras").


4. **Documentação Atualizada:**
* Qualquer alteração em APIs, banco de dados ou instruções de instalação foi devidamente documentada (seja no README, Swagger ou no PRD).


5. **Código Mesclado (Merged) e Estável:**
* O código foi integrado de forma limpa na branch principal de desenvolvimento (como a `main` ou `develop`) sem gerar conflitos e sem quebrar o sistema atual.



---


                
                
                /\/\,\,\ ,
                /        ` \'\,
               /               '/|_
              /                   /
             /                   /
            /                   ;
            ;-""-.  ____       ,
           /      )'    `.     '
          (    o |        )   ;
           ),'"""\    o   ;  :
           ;\___  `._____/ ,-:
          ;                 @ )
         /                `;-'
      ,. `-.______________,|
 ,(`._||         \__\__\__)|
,`.`-   \        '.        |
 `._  ) :          )______,;\_
    \    \_   _,--/       ,   `.
     \     `--\   :      /      `.
      \        \  ;     |         \
       `-._____ ;|      |       _,'
   -hrr-       \/'      `-.----' \
                /          \      \
