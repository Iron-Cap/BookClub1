const startButton = document.getElementById('start-btn')
const nextButton = document.getElementById('next-btn')
const questionContainerElement = document.getElementById('question-container')
const questionElement = document.getElementById('question')
const answerButtonsElement = document.getElementById('answer-buttons')

let shuffledQuestions, currentQuestionIndex

startButton.addEventListener('click', startGame)
nextButton.addEventListener('click', () => {
  currentQuestionIndex++
  setNextQuestion()
})

function startGame() {
  startButton.classList.add('hide')
  shuffledQuestions = questions.sort(() => Math.random() - .5)
  currentQuestionIndex = 0
  questionContainerElement.classList.remove('hide')
  setNextQuestion()
}

function setNextQuestion() {
  resetState()
  showQuestion(shuffledQuestions[currentQuestionIndex])
}

function showQuestion(question) {
  questionElement.innerText = question.question
  question.answers.forEach(answer => {
    const button = document.createElement('button')
    button.innerText = answer.text
    button.classList.add('btn')
    if (answer.correct) {
      button.dataset.correct = answer.correct
    }
    button.addEventListener('click', selectAnswer)
    answerButtonsElement.appendChild(button)
  })
}

function resetState() {
  clearStatusClass(document.body)
  nextButton.classList.add('hide')
  while (answerButtonsElement.firstChild) {
    answerButtonsElement.removeChild(answerButtonsElement.firstChild)
  }
}

function selectAnswer(e) {
  const selectedButton = e.target
  const correct = selectedButton.dataset.correct
  setStatusClass(document.body, correct)
  Array.from(answerButtonsElement.children).forEach(button => {
    setStatusClass(button, button.dataset.correct)
  })
  if (shuffledQuestions.length > currentQuestionIndex + 1) {
    nextButton.classList.remove('hide')
  } else {
    startButton.innerText = 'Restart'
    startButton.classList.remove('hide')
  }
}

function setStatusClass(element, correct) {
  clearStatusClass(element)
  if (correct) {
    element.classList.add('correct')
  } else {
    element.classList.add('wrong')
  }
}

function clearStatusClass(element) {
  element.classList.remove('correct')
  element.classList.remove('wrong')
}

const questions = [
  {
    question: 'Where is the rocket is launched?',
    answers: [
      { text: 'Ohio', correct: true },
      { text: 'Virginia', correct: false },
      { text: 'Mars', correct: false },
      { text: 'Spaceship', correct: false }

    ]
  },
  {
    question: 'What year and month is the book starts in?',
    answers: [
      { text: 'February, 1999', correct: true },
      { text: 'December, 2025', correct: false },
      { text: 'August, 1000', correct: false },
      { text: 'April,2059', correct: false }
    ]
  },
  {
    question: 'How are martian eyes is described in the book?',
    answers: [
      { text: 'Yellow', correct: true },
      { text: 'Red', correct: false },
      { text: 'Green', correct: false },
      { text: 'Blue', correct: false }
    ]
  },
  {
    question: 'One of the idea from this book is the author is implying that the world will come to an end using atmoic weapons',
    answers: [
      { text: 'Cool!', correct: true }
    ]
  },
  {
    question: 'Who are the two characters introduced at the beginning?',
    answers: [
      { text: 'Ylla and Yll', correct: true },
      { text: 'Mr.Iii and Mrs. Iii', correct: false },
      { text: 'Mr.Xxx and Mrs.Xxx', correct: false },
      { text: 'Mr.Www and Mrs.Www', correct: false }
    ]
  },
  {
    question: 'What happens the next morning in chapter 1?',
    answers: [
      { text: 'They leave mars and go to earth', correct: false },
      { text: 'Earth men land', correct: true },
      { text: '', correct: false },
      { text: 'Nothing', correct: false }
    ]
  },
  {
    question: 'What song does the musician sing?', 
    answers: [
      { text: 'She walks in beauty', correct: true },
      { text: 'Wonderful Tonight', correct: false }
    ]
  },
  {
    question: 'Who are they referred to are communicating with everyone?',
    answers: [
      { text: 'Mr.Xxx', correct: false },
      { text: 'Mr.Iii', correct: true },
      { text: 'Mr.Www', correct: false },
      { text: 'Mr.Sss', correct: false }
    ]
  },
  {
    question: 'What do the earth people use to communicate with the martians?',
    answers: [
      { text: 'Phones', correct: false },
      { text: 'Futuristic device', correct: false },
      { text: 'Telepathy', correct: true },
      { text: 'Talking', correct: false }
    ]
  },
  {
    question: 'Another idea from the book is that in the future robots will be part of our daily lives.',
    answers: [
      { text: 'Cool!', correct: true }
    ]
  },
  {
    question: 'Why does Mr. Xxx think the earth people are crazy?',
    answers: [
      { text: 'Because they said that mars is inhabitable', correct: false },
      { text: 'They are from earth and they dont think it exists', correct: true },
      { text: 'They landed a rocket on a house.', correct: false },
      { text: 'Because they hit him.', correct: false }
    ]
  },
  {
    question: 'What does the man that runs to the launchpad claim to be in march of 2000? ',
    answers: [
      { text: 'Banker', correct: false },
      { text: 'Taxpayer', correct: true },
      { text: 'Rocket owner', correct: false },
      { text: 'Landlord', correct: false }
    ]
  },
  {
    question: 'How big is the crew in the expedition of April ? ',
    answers: [
      { text: '20 people', correct: false },
      { text: '16 people', correct: true },
      { text: '10 people', correct: false },
      { text: '15 people', correct: false }
    ]
  },
  {
    question: 'What happens once they land in America?',
    answers: [
      { text: 'The crew find other aliens and fight.', correct: false },
      { text: 'Black finds himself in the home of his parents and his brother John.', correct: true },
      { text: 'Mr.Www comes along too find Mr.Jjj', correct: false },
      { text: 'There is noone.', correct: false }
    ]
  },
  {
    question: 'What does his brother of Black think this reunion is? ',
    answers: [
      { text: 'A good reunion', correct: false },
      { text: 'A martian trap', correct: true },
      { text: 'Its all fake and this is not ', correct: false },
      { text: 'Nothing', correct: false }
    ]
  },
  {
    question: 'What does Captain Wilder lets his men do and who gets mad?',
    answers: [
      { text: 'They drive the spaceship onto earth, the co-captain gets mad. ', correct: false },
      { text: 'They drink and dance, so this angers the archaeologist in the crew, Jeff Spender. ', correct: true },
      { text: 'He leaves his men to do work on a store, the store owner gets mad', correct: false },
      { text: 'Not in the text', correct: false }
    ]
  },
  {
    question: 'What poem does Spender recite from?',
    answers: [
      { text: 'English poem', correct: false },
      { text: 'Love poem', correct: false },
      { text: 'Byron poem', correct: true },
      { text: 'Martian poem', correct: false }
    ]
  },
  {
    question: 'What does Wilder do to Sam Parkhill, when he saw him doing target practice?',
    answers: [
      { text: 'He distracts him', correct: false },
      { text: 'He knocks his teeth out.', correct: true },
      { text: 'He grants him ownwership of a rocket', correct: false },
      { text: 'He gives him a house', correct: false }
    ]
  },
  {
    question: 'What does the settler do because of his had trouble breathing',
    answers: [
      { text: 'He moved back to earth', correct: false },
      { text: 'He started to plant oxygen-producing trees.', correct: true },
      { text: 'He started to destory other peoples property', correct: false },
      { text: 'Nothing', correct: false }
    ]
  },
  {
    question: "When Toma's Gomez is driving to a party, what does the old man say about the mars and earth?",
    answers: [
      { text: 'The old man says mars has differnet communication', correct: false },
      { text: 'The old man doesnt expect Mars to be like Earth; he anticipates differences.', correct: true },
      { text: 'He says that this land is inhabitable ', correct: false },
      { text: 'He says mars is not good for people.', correct: false }
    ]
  },

  {
    question: 'What does the light-radio message say from Australia? ',
    answers: [
      { text: 'Australia has been destroyed due to the accidental detonation of an atomic stockpile', correct: true },
      { text: 'People are not there on venus', correct: false },
      { text: 'Asutralian people fled to mars', correct: false },
      { text: 'There is no light-radio message', correct: false }
    ]
  },
  {
    question: 'What happened when three waves of the settlers landed? ',
    answers: [
      { text: 'The first built cities, second built wells , third built nothing', correct: false },
      { text: 'The first had a rough time building, the second built cities, third built american towns ', correct: true },
      { text: 'The first built nothing, second built brick houses, third built cities.', correct: false },
      { text: 'The first built nothing, second built nothing, and the third built everything', correct: false }
    ]
  },
  {
    question: 'In June of 2003, where are the group of men sitting',
    answers: [
      { text: 'Rocket', correct: false },
      { text: 'Hardware store', correct: true },
      { text: 'School', correct: false },
      { text: 'In the park', correct: false }
    ]
  },
  {
    question: 'What news is announced in June of 2003?',
    answers: [
      { text: 'People on earth are going to leave for mars', correct: false },
      { text: 'Black men and women in South america built their own rockets for mars.', correct: true },
      { text: 'Martians are coming to earth', correct: false },
      { text: 'Nothing', correct: false }
    ]
  },
  {
    question: 'From Gomez perspective how does the party that Muhe Ca dismounts go into look like? What do they next? ',
    answers: [
      { text: 'Great looking party with furturistic things', correct: false },
      { text: 'Full of robots and robotic arms', correct: true },
      { text: 'A giant festival in a town that looks deserted and ruined to Gomez.', correct: false },
      { text: 'Nothing', correct: false }
    ]
  },
  {
    question: 'What does Mr. Teece do to his employee, Silly, when he tries to leave? ',
    answers: [
      { text: 'He makes him the owner', correct: false },
      { text: 'He makes him stay because of his work contract', correct: true },
      { text: "He let's him leave ", correct: false },
      { text: 'He removes him', correct: false }
    ]
  },
  {
    question: 'What does Mr. Teece do when he sees Belter and his men walking? ',
    answers: [
      { text: 'He beats him up', correct: false },
      { text: 'He stops them and asks him to pay $50.', correct: true },
      { text: 'He going with them', correct: false },
      { text: 'He does nothing and leaves him alone.', correct: false }
    ]
  },
  {
    question: 'What is the book did William Stendahl constructed and what is filled with? ',
    answers: [
      { text: 'Book of mars and it is about building on mars', correct: false },
      { text: 'House of Usher and it is gloomy', correct: true },

    ]
  },
    {
    question: 'What happens in November of 2005 on Earth? ',
    answers: [
      { text: 'New comes that they have no more rockets on earth.', correct: false },
      { text: 'News comes from Earth that atomic war is imminent.', correct: true },
      { text: 'Martians arrive in their ships', correct: false },
      { text: 'Nothing!', correct: false }
    ]
  },
  {
    question: 'An example of the author showing that robots will be a big part of our lives in the future is when he talks about the automated house at the end. After april of 2026',
    answers: [
      { text: 'Cool!', correct: true }
    ]
  },
  {
    question: 'This book was written before a picture of mars was taken in color. So the color of mars in the book was actually black. ',
    answers: [
      { text: 'Cool!', correct: true }
    ]
  },
  {
    question: 'What type of message comes from Earth after it’s in trouble? ',
    answers: [
      { text: 'A light-radio message', correct: true },
      { text: 'A text-message', correct: false },
      { text: 'A heavy-radio message', correct: false },
      { text: 'A light message', correct: false }
    ]
  },
  {
    question: 'What happens to Sam Parkhill after he opened a hot dog stand and sees a Martian?    ',
    answers: [
      { text: 'He sees a fleet of Martian sand ships coming over.', correct: true },
      { text: 'He sells a lot of hot dogs to martians', correct: false },
      { text: 'He breaks it down because there is an invasion', correct: false },
      { text: 'Nothing!', correct: false }
    ]
  },
  {
    question: 'What does Sam parkhill and his wife, Elma, do to escape them?',
    answers: [
      { text: 'Sam tries to escape in his own stolen sand ship. ', correct: true },
      { text: 'Sam tries to destory them all, including himself', correct: false },
      { text: 'Sam tries to peace with martians', correct: false },
      { text: 'Sam tries to beat up the martian he sees. ', correct: false }
    ]
  },
  {
    question: 'What happens after Sam says, “tonight is the night” after he is captured? ',
    answers: [
      { text: 'Later that night, he sees Earth burst into flame', correct: true },
      { text: 'Later that night, he sees his people come over to mars', correct: false },
      { text: 'Later that night, he sees martians invading earth', correct: false },
      { text: 'Later that night, he sees a rocket landing on mars.', correct: false }
    ]
  },
  {
    question: 'What is the women’s favorite poem that the house reads every evening? ',
    answers: [
      { text: 'There Is No End Of Mars', correct: false },
      { text: 'There Will Come Soft Rains.', correct: true },
      { text: 'The Endless Amount Of Space', correct: false },
      { text: 'The Rocket and Space', correct: false }
    ]
  },
  {
    question: 'Who comes from a rocket to Hathaway? And from where did he return from?',
    answers: [
      { text: 'The rocket lands, and nothing happened.', correct: false },
      { text: 'The rocket lands, and Captain Wilder returned from exploring Jupiter and Pluto.', correct: true },
      { text: 'The rocket brought earth people to mars', correct: false },
      { text: 'The rocket never came.', correct: false }
    ]
  },
  



]
