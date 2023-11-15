# causality_ml_suicide_prevention


## Suicide prevention using causality in machine learning

The alarming increase in the number of people affected by mental illness has become one of the main public health problems facing governments around the world.
Suicide is among the 20 most common causes of death according to an assessment by the World Health Organization (Organization et al., 2019), surpassing malaria, breast cancer or homicide and in the last 20 years, there has been a 24% increase in cases.

In order to assist in suicide prevention, we used clinical data from outpatients to identify possible causal factors that may establish relationships with suicidal ideation. To this end, we use causal inference and machine learning methods.

The factors used for causal inference were: Sex, Marital Status, Type of Residence, Alcoholic, Drug Use, Suicide in the Family, Depression in the Family, History of alcohol use in the family, Drugs in the Family, Neurological Disease, Psychiatric Disease, Capable of enjoying things, Impact of your Family and friends, Able to make important decisions, Student, Insomnia, Anxiety, Loss of insights, Appetite, Weight loss, Somatic anxiety, Hypochondriasis, Feeling of Guilt, Work and interests, Energy, Slowness in thought and speech, Agitation, Libido, OCD and age.

After our research, the factors that presented themselves as possible causes that lead an individual to have suicidal ideation were: Suicide in the family, Able to make important decisions, Student, Hypochondriasis, Feelings of guilt, Work and interests, Depression in the family, History of use of alcohol in the family, Able to enjoy things and Use of drugs.

The objective of this project is to carry out counterfactual simulations to obtain the possible factors that influence a certain individual to have suicidal ideation.
With it, health professionals who care for patients with suicidal ideation will be able to work with them more assertively, aiming to mitigate or even eliminate such ideation.

Steps for execution:

1) Download the files: dados.csv and counterfactural_inference_new_individual.ipynb
2) Open the google colab link in a browser https://colab.research.google.com/
3) Log in with your Google account
4) Go to Upload/Browse and navigate to the folder containing the counterfactural_inference_new_individual.ipynb file. Click open
5) Upload the data.csv file by accessing the Files icon in the left corner menu, navigating to the folder containing the file. Click open and ignore the warning.
6) Access the Run environment/Run all menu
7) Enter data for each factor relating to the individual in question:
   
  	Suicide in the family: Enter 1 for Yes and 0 for No.
  
  	Drugs in the family: Enter 1 for Yes and 0 for No.
  
  	Able to make important decisions: Enter a number from 1 to 5, where: 1=I completely agree; 2=Agree; 3=Neutral; 4=Disagree; 5=I completely disagree.
  
  	Student: Enter a number from 0 to 2, where: 0=No; 1=Yes; 2=Part-time.
  
  	Hypochondriasis: Enter a number from 0 to 4, where: 0=Absent; 1=Light; 2=Moderate; 3=Moderately severe; 4=Severe.
  
  	Feelings of guilt: Enter a number from 0 to 4, where: 0=Absent; 1=Doubtful or trivial: Self-censorship, feels that he has let people down; 2=Mild: Ideas of guilt or
        rumination about past mistakes or sinful acts; 3=Moderate: Current illness is a punishment. Delusions of guilt; 4=Severe: Hears accusatory or denunciatory voices and/or
        experiences threatening visual hallucinations.
  
  	Work and interests: Enter a number from 0 to 4, where: 0=Absent: No difficulty; 1=Doubtful or trivial: Thoughts and feelings of incapacity, tiredness or weakness related
        to activities; work or hobbies; 2=Mild: Loss of interest in the activity; hobbies or work – reported directly by the patient, or indirectly in apathy, indecision and
        vacillation (feeling that they need to make an effort to work or carry out activities); 3=Moderate: Decrease in real time spent on activities or decrease in productivity;
        4=Serious: Stopped working due to current illness.

  	Depression in the family: Enter 1 for Yes and 0 for No.
   
  	History of alcohol use in the family: Enter 1 for Yes and 0 for No.
   
	Able to enjoy things: Enter a number from 1 to 5, where: 1=I completely agree; 2=Agree; 3=Neutral; 4=Disagree; 5=I completely disagree.

	Drug use: Enter a number from 0 to 2, where: 0=None verified; 1=Abuse; 2=Dependent.
  
  	Suicide: Enter a number from 0 to 4, where: : 0=Absent; 1=Feels that life is empty; 2=Death wishes; 3=Active suicidal thoughts; 4=Serious suicide attempt.
  
  	Anxiety: Enter a number from 0 to 4, where: 0=Absent: No difficulty; 1=Doubtful or trivial: Subjective tension and irritability; 2=Mild: Preoccupation with minor matters;
        3=Moderate: Apprehensive attitude apparent on face or speech; 4=Severe: Fears expressed without questioning.

9) After a few minutes, the value with the level of suicidal ideation predicted for the individual will be displayed
10) The last step is to carry out counterfactual analyzes simulating changes in each of the features.
  You can change each of the 10 factors to see if the level of suicidal ideation will be raised with the change.
  
  Note: If you need to perform more simulations, run the last cell again. Changing the value of the level of suicidal ideation in a simulation may be that the individual is 
  sensitive to the simulation factor in question.

## Prevenção do suicídio usando causalidade em aprendizado de máquina
O aumento alarmante do número de pessoas afetadas por doenças mentais tornou-se um dos principais problemas de saúde pública enfrentado pelos governos em todo o mundo.
O suicídio esta entre as 20 causas de morte mais comuns segundo avaliação da Organização Mundial da Saúde, superando malária, câncer de mama ou homicídio, e nos últimos 20 anos houve um aumento de 24% dos casos (Organization et al., 2019).

Com o objetivo de auxiliar na prevenção do suicídio, utilizamos dados clínicos de pacientes ambulatoriais para identificar os possíveis fatores causais que possam estabelecer relações com a ideação suicida. Para tanto, utilizamos métodos de inferência causal e aprendizado de máquina.

Os fatores utilizados para inferência causal foram: Sexo, Estado Civil, Tipo de Residência, Uso de Álcool, Udo de Drogas, Suicídio na Família, Depressão na Família, Histórico de uso de álcool na familia, Droga na Família, Doença Neurológica, Doença Psiquiátrica, Capaz de desfrutar das coisas, Impacto de sua Família e amigos, Capaz de tomar decisões importantes, Estudante, Insônia, Ansiedade, Perda de insights, Apetite, Perda de Peso, Ansiedade somática, Hipocondriase, Sentimento de Culpa, Trabalho e interesses, Energia, Lentidão no pensamento e na fala, Agitação, Libido, TOC e idade.

Após nossa pesquisa, os fatores que se apresentaram como possíveis causas que levam um indivíduo a ter ideação suicida foram: Suicídio na família, Capaz de tomar decisões importantes, Estudante, Hipocondriase, Sentimentos de culpa, Trabalho e interesses, Depressão na familia, Histórico de uso de álcool na familia, Capaz de desfrutar das coisas e Uso de drogas.

O objetivo desse projeto é fazer simulações contrafctuais para obter os possíveis fatores que influenciam determinado indivíduo a ter ideação suicida.
De posse do projeto, os profissionais da área de saúde que atendem pacientes com ideação suicida, poderão trabalhar com os indivíduos de forma mais assertiva objetivando atenuar ou até eliminar tal ideação.

Passos para execução:

1) No canto superior direito desta página, cliquem em ![image](https://github.com/Cristianemax/causality_ml_suicide_prevention/assets/65812157/77bf57af-2450-4075-a64a-6b40da37bfc0) e Selecione a opção "Download ZIP". Extraia o arquivo "ZIP" em uma pasta clicando com o botão direito em cima dele e posteriormente em "Extrair tudo" ![image](https://github.com/Cristianemax/causality_ml_suicide_prevention/assets/65812157/00307deb-2619-480a-8b29-493a1006585c)

2) Abra o link do google colab https://colab.research.google.com/ em um navegador (ex: google chrome)  
3) Faça o login com sua conta google no navegador clicando em ![image](https://github.com/Cristianemax/causality_ml_suicide_prevention/assets/65812157/dee6386a-fb9b-4fdb-a73f-49161bd5cbe8) no canto superior direito.
   Será aberto uma página contendo o código da aplicação.
                                                                
5) Acesse  ![image](https://github.com/Cristianemax/causality_ml_suicide_prevention/assets/65812157/9a339cba-c7b0-45f3-b4da-e99000678daf), clique em ![image](https://github.com/Cristianemax/causality_ml_suicide_prevention/assets/65812157/925a5edd-eb04-4bf4-9e9e-d4a61404c2ab)
   navegue até a pasta que contenha o arquivo simulacao_contrafactual_novo_individuo.ipynb. Clique em abrir.
   Será aberto uma página contendo o código da aplicação.
7) Clique no ícone ![image](https://github.com/Cristianemax/causality_ml_suicide_prevention/assets/65812157/737a8af9-06e8-445d-b088-3dcf1fa5604e)
 que aparece no canto esquerdo.

   Assim que o menu Arquivos aparecer, clique no ícone "Fazer upload para o armazenamento da sessão" ![image](https://github.com/Cristianemax/causality_ml_suicide_prevention/assets/65812157/d0567cb7-755e-4ea7-bc46-54f789d53f51)

 navegue até a pasta em que extraiu os arquivos no passo 1, selecione o arquivo data.csv ![image](https://github.com/Cristianemax/causality_ml_suicide_prevention/assets/65812157/02f35886-4982-46db-a0b9-7ae5ce9f1810)
 clique em abrir para fazer o upload (ignore o aviso - caso apareça).
   
9) Acesse o menu Ambiente de execução e selecione Executar tudo
    ![image](https://github.com/Cristianemax/causality_ml_suicide_prevention/assets/65812157/220672a2-6fd1-4ee3-8eba-51e5f3cac072)

11) Entre com os dados de cada fator referente ao indivíduo em questão:
   
	  Suicídio na família: Digite 1 para Sim e 0 para não. Clique em "Enter"  
   
	  Capaz de tomar decisões importantes: Digite um número de 1 a 5, sendo: 1=Concordo totalmente; 2=Concordo; 3=Neutro; 4=Discordo; 5=Discordo totalmente. Clique em "Enter"
   
	  Estudante: Digite um número de 0 a 2, sendo: 0=Não; 1=Sim; 2=Meio período. Clique em "Enter"
   
	  Hipocondriase: Digite um número de 0 a 4, sendo: 0=Ausente; 1=Leve; 2=Moderado; 3=Moderadamente grave; 4=Grave. Clique em "Enter"
   
	  Sentimentos de culpa: Digite um número de 0 a 4, sendo: 0=Ausente; 1=Duvidoso ou trivial: Autocensura, sente que decepcionou as pessoas; 2=Leve: Idéias de
          culpa ou ruminação sobre erros passados ou atos pecaminosos; 3=Moderado: A doença atual é uma punição. Delírios de culpa; 4=Grave: Ouve vozes acusatórias ou 
          denunciatórias e/ou experimenta alucinações visuais ameaçadoras. Clique em "Enter"
   
	  Trabalho e interesses: Digite um número de 0 a 4, sendo:0=Ausente: Sem dificuldade; 1=Duvidoso ou trivial: Pensamentos e sentimentos de incapacidade, cansaço
          ou fraqueza relacionados às atividades; trabalho ou hobbies; 2=Leve: Perda de interesse pela atividade; hobbies ou trabalho – relatados diretamente pelo 
          paciente, ou indiretos em apatia, indecisão e vacilação (sente que precisa se esforçar para trabalhar ou realizar atividades); 3=Moderado: Diminuição do tempo 
          real gasto nas atividades ou diminuição da produtividade; 4=Grave: Deixou de trabalhar por doença atual. Clique em "Enter"
   
	  Depressão na familia:  Digite 1 para Sim e 0 para não. Clique em "Enter"

	  Histórico de uso de álcool na familia:  Digite 1 para Sim e 0 para não. Clique em "Enter"

   	  Capaz de desfrutar das coisas: Digite um número de 1 a 5, sendo: 1=Concordo totalmente; 2=Concordo; 3=Neutro; 4=Discordo; 5=Discordo totalmente. Clique em "Enter'

   	  Uso de drogas: Digite um número de 0 a 2, sendo: 0=Nenhum verificado; 1=Abuso; 2=Dependente. Clique em "Enter"

   	  Suicidio: Digite um número de 0 a 4, sendo: : 0=Ausente; 1=Sente que a vida está vazia; 2=Desejos de morte; 3=Pensamentos suicidas ativos; 4=Tentativa grave
          de suicídio. Clique em "Enter"

   	  Ansiedade: Digite um número de 0 a 4, sendo: 0=Ausente: Sem dificuldade; 1=Duvidoso ou trivial: Tensão subjetiva e irritabilidade; 2=Leve: Preocupação com
          assuntos menores; 3=Moderado: Atitude apreensiva aparente na face ou na fala; 4=Grave: Medos expressos sem questionamento. Clique em "Enter"

13) Vá descendo a barra de rolagem que está no canto direito, acompanhando a execussão da aplicação. Após alguns minutos será exibido o valor com o nível de ideação suicida previsto para o indivíduo de acordo com os
    valores inseridos no passo 11 ![image](https://github.com/Cristianemax/causality_ml_suicide_prevention/assets/65812157/0fc12243-ac47-4c04-a22b-1a4497e3fbf7)

15) O último passo é fazer as análises contrafactuais** simulando alterações em cada um dos fatores.
Você pode alterar cada um dos 10 fatores e verificar se o nível de ideação suicida será sensibilizado com a mudança.

Obs.: Caso necessite efetuar mais simulações, execute a última célula novamente clicando no ícone ![image](https://github.com/Cristianemax/causality_ml_suicide_prevention/assets/65812157/7d9621c7-6017-495b-bbf8-545a5334fd60)
. A alteração do valor do nível de ideação suicida em alguma simulação, pode significar que o indíviduo 
      é sensível ao fator da simulação em questão. 

** O pensamento contrafactual é um tipo de pensamento imaginativo caracterizado pela simulação mental de alternativas para eventos passados visando alterar a sequência de eventos para que se chegue a um desfecho diferente daquele que de fato ocorreu. Efetuando simulações nos fatores que se apresentaram como possíveis causas da ideação suicida, é possível chegar a conclusão de qual fator seria importante trabalhar prioritariamente em cada individuo.
