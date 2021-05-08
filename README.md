

 public class About extends Me {
    public String getCurrentWorkplace(){
        return "Deputy Head of Software Development at Georgia Revenue Service";
    }

    public Set<String> getDailyKnowledge(){
        Set<String> brainCells=new HashSet<>();
        brainCells.add("Java");
        brainCells.add("Kotlin");
        brainCells.add("PL/SQL");
        brainCells.add("Typescript");
        return brainCells;
    }
}
