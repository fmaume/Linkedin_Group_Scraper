# Linkedin_Group_Scraper
Scrapper to extract member from console


## Extract member names
'''
stemp = document.querySelectorAll('.artdeco-entity-lockup__title')
result = []
for (elements of stemp){
 result.push(elements.innerText)
}
copy(result)
'''

## Extract member profile url
'''
stemp = document.querySelectorAll('[data-control-name="view_profile"]')
result = []
for (elements of stemp){
 result.push(elements.href)
}
copy(result)
'''

## Extract member headline
'''
stemp = document.querySelectorAll('.artdeco-entity-lockup__subtitle')
result = []
for (elements of stemp){
 result.push(elements.innerText)
}
copy(result)
'''
