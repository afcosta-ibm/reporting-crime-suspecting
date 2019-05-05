# Table 1. Original Table of Interface for Collecting Information (in Portuguese)

<table>
  <thead>
    <tr>
      <td>Attribute Name</td>
      <td>Description</td>
      <td>Example</td>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>ordem</td>
      <td>Ordem em que a conversa é realizada.</td>
      <td>1, 2, 3, 4, 5.</td>
    </tr>
    <tr>
      <td>texto</td>
      <td>Texto digitado pelo denunciante.</td>
      <td>Existem vários jovens fumando maconha aqui perto de casa, na praça são salvador próximo ao quartel dos bombeiros, fica aqui no bairro do flamengo na cidade do rio de janeiro. Tem uns 8 jovens de estatura mediana, uns brancos e outros negros.</td>
    </tr>
    <tr>
      <td>textoWatson</td>
      <td>Texto de resposta da conversação.</td>
      <td>CONSUMO DE DROGAS - [Denúncia]: Existem vários jovens fumando maconha aqui perto de casa, no [Endereço]: na praça são salvador próximo ao quartel dos bombeiros, fica aqui no bairro do flamengo na cidade do rio de janeiro. e com o(s) [Envolvido(s)]: Tem uns 8 jovens de estatura mediana, uns brancos e outros negros. Valida essa denúncia?</td>
    </tr>
    <tr>
      <td>idConversa</td>
      <td>Identificadorúnico da conversação.</td>
      <td>54b2ae4d-00c6-481f-90ca-6146d4794d51.</td>
    </tr>
    <tr>
      <td>intencoes</td>
      <td>Conjunto de intenções mapeadas pela API de conversação do Watson durante a denúncia.</td>
      <td nowrap>#SUBSTANCIAS-ENTORPECENTES-TIROTEIO-ENTRE-QUADRILHAS</br>
        #SUBSTANCIAS-ENTORPECENTES-TRAFICO-DE-DROGAS</br>
        #SUBSTANCIAS-ENTORPECENTES-CONSUMO-DE-DROGAS</br>
        #SUBSTANCIAS-ENTORPECENTES-APOLOGIA-AO-TRAFICO</br>
        #DENUNCIA-VALIDADA</br>
        #OUTRAS-DENUNCIAS</br>
        #INTENCAO-NAO-CAPTURADA
      </td>
    </tr>
    <tr>
      <td>entidades</td>
      <td>Conjunto de entidades mapeadas pela API de conversação do Watson durante a denúncia.</td>
      <td>@Envolvidos</br>
        @Traficante</br>
        @Arma</br>
        @Endereco</br>
        @Faccao</br>
        @Comunidade</br>
        @Apologia</br>
        @Droga
      </td>
    </tr>
    <tr>
      <td>nosVisitados</td>
      <td>Nós do diálogo visitados pela árvore de decisão da API de conversação do Watson durante a denúncia.</td>
      <td>DENUNCIA COMPLETA TRAFICO DE DROGAS</br>
        DENUNCIA COMPLETA CONSUMO DE DROGAS</br>
        DENUNCIA COMPLETA APOLOGIA</br>
        DENUNCIA COMPLETA TIROTEIO
    </td>
    </tr>
    <tr>
      <td>denuncia</td>
      <td>Variável de contexto usada para armazenar a denúncia realizada.</td>
      <td>Existem vários jovens fumando maconha aquiperto de casa, na praça são salvador próximo ao quartel dos bombeiros, fica aqui no bairro do flamengo na cidade do rio de janeiro. Tem uns 8 jovens de estatura mediana, uns brancos e outros negros.</td>
    </tr>
    <tr>
      <td>endereco</td>
      <td>Variável de contexto usada para armazenar o endereço mencionado na denúncia realizada.</td>
      <td>na praça são salvador próximo ao quartel dos bombeiros, fica aqui no bairro do flamengo na cidade do rio de janeiro.</td>
    </tr>
    <tr>
      <td>envolvidos</td>
      <td>Variável de contexto usada para armazenar os envolvidos mencionados na denúncia realizada.</td>
      <td>Tem uns 8 jovens de estatura mediana, uns brancos e outros negros.</td>
    </tr>
    <tr>
      <td>apologia</td>
      <td>Variável de contexto usada para armazenar qual tipo de apologia foi mencionada na denúncia realizada.</td>
      <td>Sexo</br>
        Drogas</br>
        Tráfico
      </td>
    </tr>
    <tr>
      <td>faccao</td>
      <td>Variável de contexto usada para armazenar qual(is) facção(ões) foram mencionada(s) na denúncia realizada.</td>
      <td>ADA</br>
        CV</br>
        Terceiro Comando
      </td>
    </tr>
    <tr>
      <td>enderecoEnvolvido</td>
      <td>Variável de contexto usada para armazenar o endereço e o envolvido mencionados na denúncia não capturadas pela solução (OUTRAS).</td>
      <td>O VIZINHO DE UM AMIGO MEU MANTÉM A MÃE DELE EM CÁRCERE PRIVADO. É UM GORDÃO QUE MORA AQUI NA VISCONDE DE PIRAJÁ 38, NO RIO DE JANEIRO, EM IPANEMA.</td>
    </tr>
    <tr>
      <td>breadcrumb</td>
      <td>Conjunto de nós visitados pela API de conversação do Watson durante a denúncia.</td>
      <td>DENUNCIA COMPLETA TRAFICO DE DROGAS</br>
        DENUNCIA COMPLETA CONSUMO DE DROGAS</br>
        DENUNCIA COMPLETA APOLOGIA</br>
        DENUNCIA COMPLETA TIROTEIO
      </td>
    </tr>
    <tr>
      <td>dataDenuncia</td>
      <td>Variável de contexto usada para armazenar a data da denúncia realizada.</td>
      <td>2017-05-25T13:24:21.179Z</td>
    </tr>
  </tbody>
</table>
