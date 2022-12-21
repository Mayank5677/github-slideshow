from rest_framework import serializers 
class CountryInfoSerializer(serializers.Serializer): 
    flag_link = serializers.URLField() 
    capital = serializers.ListField(child=serializers.CharField()) 
    largest_city = serializers.CharField() 
    official_languages = serializers.ListField(child=serializers.CharField()) 
    area_total = serializers.IntegerField() 
    population = serializers.CharField() 
    GDP_nominal = serializers.CharField()
