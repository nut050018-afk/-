`).join('');
}
function selectSubject(id){
current=id;
renderSubjects();
renderLesson();
renderQuiz();
document.getElementById('currentTitle').textContent=
subjects.find(s=>s.id===id).icon+' '+subjects.find(s=>s.id===id).name;
showMode(mode);
}
function renderLesson(){
const data=lessons[current];
document.getElementById('lessonContent').innerHTML=   DIL0   DIL1   $DIL2   DIL3;
}
