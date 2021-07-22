package com.mycompany.myapp.VaccinationCenterLocationInfo.controller;

import java.io.BufferedReader;
import java.io.IOException;
import java.io.InputStreamReader;
import java.net.HttpURLConnection;
import java.net.URL;
import java.util.Map;

import javax.servlet.http.HttpServletRequest;

import org.json.simple.JSONObject;
import org.json.simple.parser.JSONParser;
import org.json.simple.parser.ParseException;
import org.springframework.stereotype.Controller;
import org.springframework.ui.Model;
import org.springframework.web.bind.annotation.RequestMapping;
import org.springframework.web.bind.annotation.ResponseBody;

import com.fasterxml.jackson.databind.JsonMappingException;
import com.fasterxml.jackson.databind.ObjectMapper;
import com.google.gson.JsonParseException;

@Controller
public class VaccinationCoronaCenterApiController {

	@RequestMapping("/VaccinationCorona")
	@ResponseBody
	public Map<String, Object> getCoronaData(HttpServletRequest req , Model model) throws IOException, ParseException {
		//예방접종센터 위치정보 API
		  System.out.println("예방접종센터 위치정보 API");
		  String defaultPageNum = req.getParameter("defaultPageNum");
		  System.out.println("defaultPageNum =====> " + defaultPageNum);
		  String page = defaultPageNum; // 현재 page number 
		  BufferedReader br = null;
		  String urlstr = "https://api.odcloud.kr/api/15077586/v1/centers?page=1&perPage=10&serviceKey=pIjdyg6yRnPqmwfTfG4m3TIDh518lq4lqoOgjavC5e1QPr3Vut5Dri2mQXpGfX5CbeusLqm9VNvju4fmvIkv0g%3D%3D";
			URL url = new URL(urlstr);
			HttpURLConnection urlconnection = (HttpURLConnection) url.openConnection();
			urlconnection.setRequestMethod("GET");
			br = new BufferedReader(new InputStreamReader(urlconnection.getInputStream(),"UTF-8")); 
			String result = "";
			String line;
			while((line = br.readLine()) != null) { 
				result = result + line;
			}
			
			JSONParser parser = new JSONParser();
			Object object = parser.parse(result.toString()); 
			JSONObject json = (JSONObject) object;
			System.out.println(json);
		return getMapFromJsonObject(json);
		
	}

	public Map<String , Object > getMapFromJsonObject(JSONObject jsonObj){
		Map<String , Object >map = null;
		try {
			map = new ObjectMapper().readValue(jsonObj.toJSONString(),Map.class);
			System.out.println("map data ===> " + map );
			
		}catch(JsonParseException e) {
			
		}catch(JsonMappingException e) {
			
		}catch(IOException e) {
			
		}
		return map;
		
	}
}
