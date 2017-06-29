# podcast
podcast rss creator

# How to integrate

from podcast.podcast import newsfactory

def podcast(request):
    """Django view"""
    return HttpResponse(newsfactory(), content_type='application/rss+xml')
