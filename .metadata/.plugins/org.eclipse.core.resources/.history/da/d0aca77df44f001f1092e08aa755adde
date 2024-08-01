package MavenActivity;

import java.util.*;

public class SortedMap {

	public static void main(String[] args) {
		SortedMap<String, List<String>> marketProjectsMap = new TreeMap<>();
		 addProjectToMarket(marketProjectsMap, "Finance", "Project A");
		        addProjectToMarket(marketProjectsMap, "Finance", "Project B");
		        addProjectToMarket(marketProjectsMap, "Technology", "Project C");
		        addProjectToMarket(marketProjectsMap, "Healthcare", "Project D");
		        addProjectToMarket(marketProjectsMap, "Technology", "Project E");
		        for (String market : marketProjectsMap.keySet()) {
		            System.out.println("Market: " + market);
		            List<String> projects = marketProjectsMap.get(market);
		            for (String project : projects) {
		                System.out.println("  Project: " + project);
		            }
		        }
		    }
		    private static void addProjectToMarket(SortedMap<String, List<String>> map, String market, String project) {
		        if (map.containsKey(market)) {
		            map.get(market).add(project);
		        } else {
		            List<String> projects = new ArrayList<>();
		            projects.add(project);
		            map.put(market, projects);
		        }
		    }

}


