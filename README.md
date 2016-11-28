# essaye
public class Personne {
	private String Nom ;
	private String Prenom ;
	private int Age ;
	protected double Ressources ;
	private double Job ;
	private double Autre ;
	public double getAutre() {
		return Autre;
	}
	public void setAutre(double autre) {
		Autre = autre;
	}
	public Personne(){
	}
	public Personne(String Nom,String Prenom,double Ressources,double Job,double Autre){
		this.Nom = Nom;
		this.Prenom=Prenom;
		this.Ressources=Ressources ;
		this.Autre =Autre ;
	}
	public String getNom() {
		return Nom;
	}
	public void setNom(String nom) {
		Nom = nom;
	}
	public String getPrenom() {
		return Prenom;
	}
	public void setPrenom(String prenom) {
		Prenom = prenom;
	}
	public int getAge() {
		return Age;
	}
	public void setAge(int age) {
		Age = age;
	}
	public double getRessources() {
		return Ressources;
	}
	public void setRessources(double ressources) {
		Ressources = ressources;
	}
	public double getJob() {
		return Job;
	}
	public void setJob(double job) {
		Job = job;
	}
	public double Budget(double Job,double autre){
		
				Ressources = Job+ Autre;
				return Ressources ;
	}
		
	public void Afficher (){
		System.out.println("Nom:"+Nom);
		System.out.println("Prenom:"+Prenom);
		System.out.println("Age:"+Age);
		System.out.println("Ressources"+Ressources);
	}
	
	
}
