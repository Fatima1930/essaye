public class Etudiant extends Personne {
	
	
	private double Bourse ;
	private double AideFamilial ;
	public Etudiant (){
		
	}
	public Etudiant (String Nom, String Prenom ,int Age,double Ressources,double Job,double Autre ){
		super(Nom,Prenom,Age,Ressources,Job);
	this.Bourse=Bourse ;
	this.AideFamilial = AideFamilial ;
}
	public double getBourse() {
		return Bourse;
	}
	public void setBourse(double Bourse) {
		Bourse = Bourse;
	}
	public double getAideFamilial() {
		return AideFamilial;
	}
	public void setAideFamilial(double aideFamilial) {
		AideFamilial = AideFamilial;
	}
	public void afficher2(){
		super.Afficher();
		
	}
	public double Budget2(){
		
		 super.Budget(Bourse,AideFamilial);
		 return Ressources ;
	}
	
	

}
